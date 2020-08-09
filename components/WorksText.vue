<template>
  <div class="works-text">
    <img-loader alt="users" name="pic2"></img-loader>
    <h3 class="uppercase text-xs lg:text-lg py-3">creatively designed</h3>
    <p class="italic hidden sm:block text-sm lg:text-base">Lorem ipsum dolor sit</p>
  </div>
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
.works-text {
  @apply grid self-center hidden text-white font-Montserrat items-center;
}

.works-content:hover .works-text {
  @apply block absolute z-50 flex flex-col justify-center;
  top: 50%;
  left: 50%;
  margin-right: -50%;
  transform: translate(-50%, -50%)
}
</style>
