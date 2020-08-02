<template>
  <li class="header-anchor"><a href="#"><slot>Name</slot></a></li>
</template>

<script>

</script>

<style>
.header-anchor {
  @apply w-1/4 relative text-left pt-2;
  &:hover {
    &::before {
      @apply absolute border-t-2  border-red-600 inset-0 z-10;
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
