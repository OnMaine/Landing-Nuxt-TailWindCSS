<template>
  <section>
    <div class="container bg-white font-Montserrat mx-auto text-center mt-20">
      <div>
        <span class="text-xl font-Kaushan">What we do</span>
        <h1 class="uppercase text-2xl font-Montserrat font-bold tracking-tighter mt-2">Some of our work</h1>
      </div>
      <div class="border-b-4 border-red-400 w-16 mx-auto my-8"></div>
      <p class="font-Roboto text-sm w-3/4 mx-auto mb-24 text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
        Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
    </div>
    <works-galery></works-galery>
  </section>
</template>

<script>
import WorksGalery from '@/components/WorksGalery'

export default {
  components: {
    WorksGalery
  }
};
</script>

<style>

</style>
