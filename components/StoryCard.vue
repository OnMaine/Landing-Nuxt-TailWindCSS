<template>
  <div class="section-image">
    <slot>Image</slot>
  </div>
</template>

<style>
.section-image {
  @apply relative z-0 grid;
  &:hover {
    @apply cursor-pointer;
    &::after {
      @apply absolute w-full h-full bg-teal-300;
	     content: "";
       top: 10px;
       left: 10px;
       z-index: -1;
    }
    &::before {
      @apply absolute w-full h-full z-10 flex;
       content: "";
       background: linear-gradient(#db7474, #e3cc7c);
       opacity: 0.9;
    }
  }
}
</style>
