<template>
  <div class="coments-stats-wrap">
    <slot>wrapp</slot>
  </div>
</template>

<style>
.coments-stats-wrap {
  @apply grid grid-cols-2 self-center justify-center;
}

.coments-stats-wrap img {
  @apply pt-1 pr-3;
}

.coments-stats span {
  @apply text-sm italic text-gray-600;
  &:hover {
    @apply underline cursor-pointer text-orange-400;
  }
}
</style>
