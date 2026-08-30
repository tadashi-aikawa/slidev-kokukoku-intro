<script setup lang="ts">
import { onSlideEnter, onSlideLeave } from "@slidev/client"
import { nextTick, ref } from "vue"

defineProps<{
  src: string
  alt: string
}>()

const image = ref<HTMLImageElement | null>(null)
const viewport = ref<HTMLElement | null>(null)
let frameId = 0
let timeoutId = 0
let runId = 0
let scrollAnimation: Animation | null = null

function cancelScroll() {
  runId += 1
  cancelAnimationFrame(frameId)
  window.clearTimeout(timeoutId)
  scrollAnimation?.cancel()
  scrollAnimation = null
  const target = image.value
  if (!target) return
  target.style.transition = "none"
  target.style.transform = "translateY(0)"
  target.style.opacity = "1"
}

async function startScroll() {
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
  target.style.transition = "none"
  target.style.transform = "translateY(0)"
  target.style.opacity = "1"
  void target.offsetHeight

  timeoutId = window.setTimeout(() => {
    if (currentRun !== runId) return
    frameId = requestAnimationFrame(() => {
      frameId = requestAnimationFrame(() => {
        if (window.matchMedia("(prefers-reduced-motion: reduce)").matches) return

        const position = (ratio: number) => `translateY(-${Math.round(distance * ratio)}px)`
        scrollAnimation = target.animate([
          { offset: 0, transform: position(0), opacity: 1 },
          { offset: 0.18, transform: position(0.035), opacity: 1 },
          { offset: 0.2, transform: position(0.035), opacity: 0 },
          { offset: 0.205, transform: position(0.32), opacity: 0 },
          { offset: 0.225, transform: position(0.32), opacity: 1 },
          { offset: 0.405, transform: position(0.355), opacity: 1 },
          { offset: 0.425, transform: position(0.355), opacity: 0 },
          { offset: 0.43, transform: position(0.72), opacity: 0 },
          { offset: 0.45, transform: position(0.72), opacity: 1 },
          { offset: 0.63, transform: position(0.755), opacity: 1 },
          { offset: 0.65, transform: position(0.755), opacity: 0 },
          { offset: 0.655, transform: position(0.92), opacity: 0 },
          { offset: 0.675, transform: position(0.92), opacity: 1 },
          { offset: 1, transform: position(1), opacity: 1 },
        ], {
          duration: 26000,
          easing: "linear",
          fill: "forwards",
        })
      })
    })
  }, 600)
}

onSlideEnter(startScroll)
onSlideLeave(cancelScroll)
</script>

<template>
  <div ref="viewport" class="kk-article-viewport">
    <img ref="image" class="kk-article-capture" :src="src" :alt="alt" />
  </div>
</template>
