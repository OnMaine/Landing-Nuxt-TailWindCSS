<template>
  <section style="background-image: url(/mobile.png) no-repeat; background-size: cover;">
    <div class="font-Montserrat container mx-auto text-center">
      <div class="pt-20">
        <span class="text-xl font-Kaushan">For all devices</span>
        <h1 class="uppercase text-2xl font-Montserrat font-bold tracking-tighter mt-2">Unique design</h1>
      </div>
      <div class="border-b-4 border-red-400 w-16 mx-auto mt-8"></div>
    </div>
    <div class="container mx-auto flex justify-center">
      <div class="mobile-img">
        <img src="/laptop.png" alt="Design">
      </div>
    </div>
  </section>
</template>

<script>
export default {

};
</script>

<style>
.mobile-img {
  @apply relative z-0 inline-block;
  &::before {
    @apply absolute z-10;
    content: url(/phone.png);
    top: 38%;
    left: 70%;
  }
}
</style>
