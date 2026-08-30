<script setup lang="ts">
import { computed, onBeforeUnmount, ref } from "vue"

const currentTime = ref(0)
let frameId = 0
let videoElement: HTMLVideoElement | null = null

const lerp = (from: number, to: number, progress: number) => from + (to - from) * progress

const visual = computed(() => {
  const time = currentTime.value % 9

  if (time < 3) {
    return { weights: [1, 0, 0], hour: 285, minute: 180 }
  }
  if (time < 3.35) {
    const progress = (time - 3) / 0.35
    return {
      weights: [1 - progress, progress, 0],
      hour: lerp(285, 297.5, progress),
      minute: lerp(180, 330, progress),
    }
  }
  if (time < 6) {
    return { weights: [0, 1, 0], hour: 297.5, minute: 330 }
  }
  if (time < 6.35) {
    const progress = (time - 6) / 0.35
    return {
      weights: [0, 1 - progress, progress],
      hour: lerp(297.5, 300, progress),
      minute: lerp(330, 360, progress),
    }
  }
  if (time < 8.3) {
    return { weights: [0, 0, 1], hour: 300, minute: 360 }
  }
  if (time < 8.65) {
    const progress = (time - 8.3) / 0.35
    return {
      weights: [progress, 0, 1 - progress],
      hour: lerp(300, 285, progress),
      minute: lerp(360, 180, progress),
    }
  }
  return { weights: [1, 0, 0], hour: 285, minute: 180 }
})

function updateFromVideo() {
  if (!videoElement) return
  currentTime.value = videoElement.currentTime
  frameId = requestAnimationFrame(updateFromVideo)
}

function handlePlay(event: Event) {
  videoElement = event.currentTarget as HTMLVideoElement
  cancelAnimationFrame(frameId)
  updateFromVideo()
}

function handleTimeUpdate(event: Event) {
  videoElement = event.currentTarget as HTMLVideoElement
  currentTime.value = videoElement.currentTime
}

function handlePause() {
  cancelAnimationFrame(frameId)
}

onBeforeUnmount(() => cancelAnimationFrame(frameId))
</script>

<template>
  <div class="kk-sync-stage">
    <div class="kk-big-clock" aria-label="09時30分から10時へ進む時計">
      <div class="kk-clock-face">
        <i class="kk-clock-hand kk-hour" :style="{ transform: `rotate(${visual.hour}deg)` }"></i>
        <i class="kk-clock-hand kk-minute" :style="{ transform: `rotate(${visual.minute}deg)` }"></i>
        <i class="kk-clock-pin"></i>
      </div>
      <div class="kk-clock-times">
        <span :style="{ opacity: visual.weights[0] }">09:30</span>
        <span :style="{ opacity: visual.weights[1] }">09:55</span>
        <span :style="{ opacity: visual.weights[2] }">10:00</span>
      </div>
      <div class="kk-triad-phase">
        <span :style="{ opacity: visual.weights[0] }">作業を記録</span>
        <span :style="{ opacity: visual.weights[1] }">予定が光る</span>
        <span :style="{ opacity: visual.weights[2] }">予定が始まる</span>
      </div>
    </div>
    <div class="kk-triad-video">
      <SlidevVideo
        autoplay
        loop
        muted
        playsinline
        @play="handlePlay"
        @pause="handlePause"
        @timeupdate="handleTimeUpdate"
      >
        <source src="../public/media/demo-time-flow-panel.mp4" type="video/mp4" />
      </SlidevVideo>
    </div>
  </div>
</template>
