<template>
  <button class="header-btn">
    <slot>Button</slot>
  </button>
</template>

<style>
.header-btn {
  @apply uppercase font-bold py-2 px-6 border-2 border-white;
  &:hover {
    @apply bg-red-400 border-orange-300;
  }
}
</style>
