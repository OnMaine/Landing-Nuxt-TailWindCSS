<template>
  <header class="bg-cover bg-center text-white text-center font-Montserrat" style="background-image: url(/bg.png)">
    <div class="container mx-auto">
      <Navbar/>
      <div class="py-24 flex-col justify-center">
        <span class="text-4xl font-Kaushan">Creative Template</span>
        <h1 class="uppercase text-6xl font-bold">Welcome <br> to MoGo</h1>
        <div class="border-b-4 w-16 mx-auto my-8"></div>
        <n-link to="about">
          <h-button>Learn More</h-button>
        </n-link>
      </div>
      <div class="mt-2">
        <ul class="flex flex-wrap pb-2">
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
