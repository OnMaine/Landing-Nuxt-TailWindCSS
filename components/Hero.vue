<template>
  <header class="h-screen w-screen bg-cover bg-center text-white text-center" style="background-image: url(/_nuxt/static/bg.png)">
    <div class="container mx-auto">
      <Navbar/>
      <div class="py-24 flex-col justify-center">
        <span class="text-4xl">Creative Template</span>
        <h1 class="uppercase text-6xl">Welcome <br> to MoGo</h1>
        <div class="border-b-4 w-16 mx-auto my-8"></div>
        <n-link to="about">
          <h-button>Learn More</h-button>
        </n-link>
      </div>
      <div>
        <ul class="flex flex-wrap">
          <h-anchor class="one"><span class="pr-1 font-bold">01</span>Intro</h-anchor>
          <h-anchor class="two"><span class="pr-1 font-bold">02</span>Work</h-anchor>
          <h-anchor class="three"><span class="pr-1 font-bold">03</span>About</h-anchor>
          <h-anchor class="four"><span class="pr-1 font-bold">04</span>Contacts</h-anchor>
        </ul>
      </div>
    </div>
  </header>
</template>

<script>
import Navbar from '@/components/Navbar';
import HButton from '~/components/HButton';
import HAnchor from '~/components/HAnchor';

export default {
  components: {
    Navbar,
    HButton,
    HAnchor
  }
};
</script>

</script>

<style>

</style>
