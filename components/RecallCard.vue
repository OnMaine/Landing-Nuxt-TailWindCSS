<template>
  <div class="recall-card">
    <slot>User</slot>
  </div>
</template>

<style>
.recall-card {
  @apply grid grid-cols-3 w-full text-left pb-20;
}

.recall-card img {
  @apply pl-10;
}


</style>
