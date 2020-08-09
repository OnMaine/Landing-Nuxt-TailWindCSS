<template>
  <section class="mobile">
    <div class="font-Montserrat container mx-auto text-center">
      <div class="pt-20">
        <span class="text-xl font-Kaushan">For all devices</span>
        <h1 class="uppercase text-2xl font-Montserrat font-bold tracking-tighter mt-2">Unique design</h1>
      </div>
      <div class="border-b-4 border-red-400 w-16 mx-auto mt-8"></div>
    </div>
    <div class="container mx-auto flex justify-center">
      <div class="mobile-img">
        <img-loader name="laptop"></img-loader>
      </div>
    </div>
  </section>
</template>

<script>
import ImgLoader from '~/components/ImgLoader';

export default {
  components: {
    ImgLoader,
  }
};
</script>

<style>
.mobile {
  @apply bg-cover;
  background-image: url("~assets/img/mobile.png");
}

.mobile-img {
  @apply relative z-0 inline-block;
  &::before {
    @apply absolute z-10 hidden;
    content: url("~assets/img//phone.png");
    top: 38%;
    left: 70%;
    @screen md {
      @apply block;
    }
  }
}
</style>
