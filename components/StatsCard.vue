<template>
  <div class="stats-card">
    <slot>Text</slot>
  </div>
</template>

<style>
.stats-card {
  @apply uppercase font-Montserrat text-center text-white py-12 border-l;
  &:last-child {
    @apply border-r;
  }
}
</style>
