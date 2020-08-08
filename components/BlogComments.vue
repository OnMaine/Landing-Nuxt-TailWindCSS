<template>
  <div class="coments-stats">
    <slot>stats</slot>
  </div>
</template>

<style>
.coments-stats {
  @apply grid grid-cols-4 grid-flow-col self-start pt-2;
}
</style>
