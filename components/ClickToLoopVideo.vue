<script setup lang="ts">
import { onSlideEnter, onSlideLeave, useNav } from "@slidev/client"
import { nextTick, ref, watch } from "vue"

const props = withDefaults(defineProps<{
  src: string
  previewTime?: number
  hideUntilClick?: boolean
}>(), {
  previewTime: 0,
  hideUntilClick: false,
})

const emit = defineEmits<{
  play: [video: HTMLVideoElement]
  pause: [video: HTMLVideoElement]
  timeupdate: [video: HTMLVideoElement]
}>()

const video = ref<HTMLVideoElement | null>(null)
const active = ref(false)
const revealed = ref(false)
const requestedPlayback = ref(false)
const { clicks } = useNav()
let playbackRun = 0

function showPreview() {
  playbackRun += 1
  requestedPlayback.value = false
  const target = video.value
  if (!target) return
  target.pause()
  target.currentTime = props.previewTime
  if (props.hideUntilClick) revealed.value = false
}

function handleLoadedMetadata() {
  if (!requestedPlayback.value) showPreview()
}

async function playFromStart() {
  const target = video.value
  if (!target) return
  const currentRun = ++playbackRun
  requestedPlayback.value = true
  revealed.value = true
  await nextTick()
  target.pause()
  target.currentTime = 0
  try {
    await target.play()
  }
  catch {
    if (currentRun === playbackRun) showPreview()
  }
}

watch(clicks, (current, previous) => {
  if (!active.value) return
  if (current > 0 && previous === 0) void playFromStart()
  if (current === 0) showPreview()
})

onSlideEnter(async (to, from) => {
  const enteredBackward = from !== undefined && from > to
  active.value = true
  await nextTick()
  requestAnimationFrame(() => {
    if (!active.value) return
    if (enteredBackward || clicks.value > 0) void playFromStart()
    else showPreview()
  })
})

onSlideLeave(() => {
  active.value = false
  showPreview()
})
</script>

<template>
  <div class="kk-click-video">
    <video
      ref="video"
      :class="{ 'kk-click-video-hidden': hideUntilClick && !revealed }"
      loop
      muted
      playsinline
      preload="auto"
      @loadedmetadata="handleLoadedMetadata"
      @play="emit('play', video!)"
      @pause="emit('pause', video!)"
      @timeupdate="emit('timeupdate', video!)"
    >
      <source :src="src" type="video/mp4" />
    </video>
    <span v-click class="kk-video-click-trigger" aria-hidden="true"></span>
  </div>
</template>
