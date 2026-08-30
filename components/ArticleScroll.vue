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

function cancelScroll() {
  runId += 1
  cancelAnimationFrame(frameId)
  window.clearTimeout(timeoutId)
  const target = image.value
  if (!target) return
  target.style.transition = "none"
  target.style.transform = "translateY(0)"
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
  void target.offsetHeight

  timeoutId = window.setTimeout(() => {
    if (currentRun !== runId) return
    frameId = requestAnimationFrame(() => {
      frameId = requestAnimationFrame(() => {
        target.style.transition = "transform 24.4s linear"
        target.style.transform = `translateY(-${distance}px)`
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
