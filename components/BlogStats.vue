<template>
  <div class="coments-stats-count">
    <slot>stats</slot>
  </div>
</template>

<style>
.coments-stats-count {
  @apply grid grid-cols-2 self-center justify-center;
}

.coments-stats-count img {
  @apply pt-1 pr-3;
}

.coments-stats span {
  @apply text-sm italic text-gray-600;
  &:hover {
    @apply underline cursor-pointer text-orange-400;
  }
}
</style>
