<template>
  <div class="recall-card grid grid-cols-2 md:grid-cols-3">
    <slot>User</slot>
  </div>
</template>

<style>
.recall-card {
  @apply w-full text-left pb-20 p-5;
}

</style>
