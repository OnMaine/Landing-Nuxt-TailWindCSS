<template>
  <section style="background-image: url(/recall.png)">
    <div class="container font-Montserrat mx-auto text-center py-24">
      <div class="pt-24">
        <span class="text-xl font-Kaushan">Heppy Clients</span>
        <h1 class="uppercase text-2xl font-Montserrat font-bold tracking-tighter mt-2">What people say</h1>
      </div>
      <div class="border-b-4 border-red-400 w-16 mx-auto my-8"></div>
    </div>
    <div class="container mx-auto grid grid-cols-2 grid-rows-2">
      <recall-card>
        <img src="/user1.png" alt="">
        <div class="recall-text">
          <h3>Matthew Dix</h3>
          <h4>Graphic Design</h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim.</p>
        </div>
      </recall-card>
      <recall-card>
        <img src="/user3.png" alt="">
        <div class="recall-text">
          <h3>Jaelynn Castillo</h3>
          <h4>Graphic Design</h4>
          <p>Ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam</p>
        </div>
      </recall-card>
      <recall-card>
        <img src="/user4.png" alt="">
        <div class="recall-text">
          <h3>Nick Karvounis</h3>
          <h4>Graphic Design</h4>
          <p>Sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam</p>
        </div>
      </recall-card>
      <recall-card>
        <img src="/user5.png" alt="">
        <div class="recall-text">
          <h3>Mike Petrucci</h3>
          <h4>Graphic Design</h4>
          <p>Dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim.</p>
        </div>
      </recall-card>
    </div>
  </section>
</template>

<script>
import RecallCard from '~/components/RecallCard';

export default {
  components: {
    RecallCard,
  }
};
</script>

<style>

.recall-text {
  @apply col-span-2;
}

.recall-text h4 {
  @apply font-Roboto italic text-gray-600 pb-10 relative z-0;
  &::before {
    @apply border-b-4 border-red-400 w-20 absolute;
    content: "";
    top: 65%;
  }
}

.recall-text h3 {
  @apply font-Montserrat uppercase text-black font-bold pb-2;
}

.recall-text p {
  @apply font-Roboto text-gray-600 text-sm;
}
</style>
