<template>
  <li class="header-anchor"><slot>Name</slot></li>
</template>

<script>

</script>

<style>
.header-anchor {
  @apply w-1/4 relative text-left pt-2;
  &:hover {
    @apply text-red-400 font-bold cursor-pointer;
    &::before {
      @apply absolute border-t-2  border-red-400 inset-0 z-10;
      content: '';
      width: 18.75%;;
    }
  }
  &::after {
    @apply absolute border-t-2  border-white inset-0 w-3/4 z-0;
    content: '';
  }
  &.one{
    &:hover {
      &::before {
        @apply left-0;
      }
    }
  }
  &.two{
    &:hover {
      &::before {
        left: calc(0% + 18.75%);
      }
    }
  }
  &.three{
    &:hover {
      &::before {
        left: calc(0% + 18.75% *2);
      }
    }
  }
  &.four{
    &:hover {
      &::before {
        left: calc(0% + 18.75% *3);
      }
    }
  }
}
</style>
