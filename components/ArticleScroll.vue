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
  const startPosition = `translateY(-${Math.round(distance * 0.3)}px)`
  const endPosition = `translateY(-${Math.round(distance * 0.5)}px)`
  target.style.transition = "none"
  target.style.transform = startPosition
  target.style.opacity = "1"
  void target.offsetHeight

  timeoutId = window.setTimeout(() => {
    if (currentRun !== runId) return
    frameId = requestAnimationFrame(() => {
      frameId = requestAnimationFrame(() => {
        if (window.matchMedia("(prefers-reduced-motion: reduce)").matches) return

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
