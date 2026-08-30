<script setup lang="ts">
import { onSlideEnter, onSlideLeave, useNav } from "@slidev/client"
import { nextTick, ref, watch } from "vue"

defineProps<{
  src: string
  alt: string
}>()

const image = ref<HTMLImageElement | null>(null)
const viewport = ref<HTMLElement | null>(null)
const active = ref(false)
const { clicks } = useNav()
let frameId = 0
let runId = 0
let scrollAnimation: Animation | null = null

function cancelScroll() {
  runId += 1
  cancelAnimationFrame(frameId)
  scrollAnimation?.cancel()
  scrollAnimation = null
}

async function prepareScroll(animate: boolean) {
  cancelScroll()
  const currentRun = runId
  await nextTick()

  const target = image.value
  const frame = viewport.value
  if (!target || !frame) return

  if (!target.complete) {
    await new Promise<void>((resolve) => target.addEventListener("load", () => resolve(), { once: true }))
  }
  if (currentRun !== runId) return

  const distance = Math.max(0, target.getBoundingClientRect().height - frame.clientHeight)
  const startPosition = `translateY(-${Math.round(distance * 0.3)}px)`
  const endPosition = `translateY(-${Math.round(distance * 0.5)}px)`
  target.style.transition = "none"
  target.style.transform = startPosition
  target.style.opacity = "1"
  void target.offsetHeight

  if (!animate || window.matchMedia("(prefers-reduced-motion: reduce)").matches) return

  frameId = requestAnimationFrame(() => {
    frameId = requestAnimationFrame(() => {
      if (currentRun !== runId) return
      scrollAnimation = target.animate([
        { transform: startPosition },
        { transform: endPosition },
      ], {
        duration: 26000,
        easing: "linear",
        fill: "forwards",
      })
    })
  })
}

watch(clicks, (current, previous) => {
  if (!active.value) return
  if (current > 0 && previous === 0) void prepareScroll(true)
  if (current === 0) void prepareScroll(false)
})

onSlideEnter(() => {
  active.value = true
  void prepareScroll(false)
})

onSlideLeave(() => {
  active.value = false
  cancelScroll()
})
</script>

<template>
  <div ref="viewport" class="kk-article-viewport">
    <img ref="image" class="kk-article-capture" :src="src" :alt="alt" />
    <span v-click class="kk-video-click-trigger" aria-hidden="true"></span>
  </div>
</template>
