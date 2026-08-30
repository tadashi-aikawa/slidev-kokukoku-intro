<template>
  <footer
    v-if="$nav.currentLayout !== 'cover'"
    class="kokukoku-page-number"
  >
    {{ $nav.currentPage }} / {{ $nav.total }}
  </footer>
</template>

<style scoped>
.kokukoku-page-number {
  position: absolute;
  top: 18px;
  right: 30px;
  z-index: 20;
  color: #ab8a55;
  font-family: "Zen Old Mincho", "Hiragino Mincho ProN", serif;
  font-size: 13px;
  letter-spacing: 0.18em;
  opacity: 0.72;
  pointer-events: none;
  view-transition-name: none;
}
</style>
