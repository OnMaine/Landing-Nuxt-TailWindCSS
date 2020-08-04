<template>
  <li class="presentation-tab">
    <slot>tab</slot>
  </li>
</template>

<style>
.presentation-tab {
  @apply mb-6 border border-gray-300;
  & h1 {
    @apply font-medium uppercase text-gray-700 relative my-5 pl-5 cursor-pointer outline-none;
    &::before {
      @apply absolute text-center;
    }
    &:focus::before {
      @apply transform rotate-180;
    }
    &:focus ~ p {
      @apply block;
    }
  }
  & p  {
    @apply overflow-y-scroll whitespace-pre-line px-5 py-4 hidden border-t border-gray-300 text-gray-600;
  }
}

li h1::before {
  content: url("~assets/img/chevron.svg");
  left: 95%;
}

li h1:focus::before {
  top: -15%;
}

li p {
  max-height: 180px;
}
</style>
