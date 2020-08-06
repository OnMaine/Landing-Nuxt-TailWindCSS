<template>
  <div class="works-text">
    <img src="/pic2.png" alt="users">
    <h3 class="uppercase text-lg py-3">creatively designed</h3>
    <p class="italic text-sm">Lorem ipsum dolor sit</p>
  </div>
</template>

<script>

</script>

<style>
.works-text {
  @apply hidden text-white font-Montserrat items-center;
}

.works-content:hover .works-text {
  @apply block absolute z-50 flex flex-col justify-center;
  top: 45%;
  left: 25%;
}
</style>
