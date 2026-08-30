<script setup lang="ts">
import { onSlideEnter, onSlideLeave, useNav } from "@slidev/client"
import { nextTick, ref, watch } from "vue"

const props = withDefaults(defineProps<{
  src: string
  previewTime?: number
}>(), {
  previewTime: 0,
})

const emit = defineEmits<{
  play: [video: HTMLVideoElement]
  pause: [video: HTMLVideoElement]
  timeupdate: [video: HTMLVideoElement]
}>()

const video = ref<HTMLVideoElement | null>(null)
const active = ref(false)
const { clicks } = useNav()

function showPreview() {
  const target = video.value
  if (!target) return
  target.pause()
  target.currentTime = props.previewTime
}

async function playFromStart() {
  const target = video.value
  if (!target) return
  target.pause()
  target.currentTime = 0
  try {
    await target.play()
  }
  catch {
    showPreview()
  }
}

watch(clicks, (current, previous) => {
  if (!active.value) return
  if (current > 0 && previous === 0) void playFromStart()
  if (current === 0) showPreview()
})

onSlideEnter(async () => {
  active.value = true
  await nextTick()
  showPreview()
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
      loop
      muted
      playsinline
      preload="auto"
      @loadedmetadata="showPreview"
      @play="emit('play', video!)"
      @pause="emit('pause', video!)"
      @timeupdate="emit('timeupdate', video!)"
    >
      <source :src="src" type="video/mp4" />
    </video>
    <span v-click class="kk-video-click-trigger" aria-hidden="true"></span>
  </div>
</template>
