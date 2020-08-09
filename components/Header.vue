<template>
  <header class="header">
    <div class="container mx-auto">
      <Navbar/>
      <div class="py-24 flex-col justify-center">
        <span class="text-4xl font-Kaushan">Creative Template</span>
        <h1 class="uppercase text-4xl sm:text-6xl font-bold">Welcome <br> to MoGo</h1>
        <div class="border-b-4 w-16 mx-auto my-8"></div>
          <h-button>Learn More</h-button>
      </div>
      <div class="mt-2">
        <ul class="grid grid-cols-2 sm:grid-cols-4 pb-2 pl-5 text-xs sm:text-lg uppercase">
          <h-anchor class="one"><a :href="'#intro'"><span class="pr-1 font-bold">01</span>Intro</a></h-anchor>
          <h-anchor class="two"><a :href="'#work'"><span class="pr-1 font-bold">02</span>Work</a></h-anchor>
          <h-anchor class="three"><a :href="'#recall'"><span class="pr-1 font-bold">03</span>About</a></h-anchor>
          <h-anchor class="four"><a :href="'#contacts'"><span class="pr-1 font-bold">04</span>Contacts</a></h-anchor>
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

<style>

.header {
  @apply bg-cover bg-center text-white text-center font-Montserrat;
  background-image: url("~assets/img/bg.png");
}

</style>
