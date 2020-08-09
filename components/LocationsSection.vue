<template>
  <section class="location flex justify-center items-center">
    <div class="container mx-auto text-center">
      <img-loader class="mx-auto" name="pin"></img-loader>
      <h2 class="map-text">Open Map</h2>
      <div class="border-b-4 border-red-400 w-24 mx-auto mt-3"></div>
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
.location {
  height: 200px;
  cursor: pointer;
}

.map-text {
  @apply uppercase text-3xl font-bold;
  color: #f38181;
}

.location {
  @apply bg-cover;
  background-image: url("~assets/img/map.png");
}

</style>
