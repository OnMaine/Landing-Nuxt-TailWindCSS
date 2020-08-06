<template>
  <section>
    <div class="bg-white font-Montserrat container mx-auto text-center mt-20">
      <div>
        <span class="text-xl font-Kaushan">What we do</span>
        <h1 class="uppercase text-2xl font-Montserrat font-bold tracking-tighter mt-2">Story about us</h1>
      </div>
      <div class="border-b-4 border-red-400 w-16 mx-auto my-8"></div>
      <p class="font-Roboto text-sm w-3/4 mx-auto mb-24 text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
        Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
    </div>
    <div class="container mx-auto flex flex-row justify-around mb-32">
      <div class="story-image">
        <story-card>
          <img src="/card1.png" alt="computer">
          <div class="story-image-text">
            <img src="/USERS.png" alt="users">
            <h3>Super Team</h3>
          </div>
        </story-card>
      </div>
      <div class="story-image">
        <story-card>
          <img src="/card2.png" alt="table1">
          <div class="story-image-text">
            <img src="/USERS.png" alt="users">
            <h3>Super Team</h3>
          </div>
        </story-card>
      </div>
      <div class="story-image">
        <story-card>
          <img src="/card3.png" alt="table2">
          <div class="story-image-text">
            <img src="/USERS.png" alt="users">
            <h3>Super Team</h3>
          </div>
        </story-card>
      </div>
    </div>
  </section>
</template>

<script>
import StoryCard from '~/components/StoryCard';

export default {
  components: {
    StoryCard,
  }
};
</script>

<style>
.story-image-text {
  @apply hidden text-white uppercase font-bold font-Montserrat items-center;
}

.story-image:hover .story-image-text {
  @apply block absolute z-50 flex flex-col justify-center;
  top: 40%;
  left: 35%;
}

</style>
