<template>
  <section id="intro">
    <div class="bg-white font-Montserrat container mx-auto text-center pt-20">
      <div>
        <span class="text-xl font-Kaushan">What we do</span>
        <h1 class="uppercase text-2xl font-Montserrat font-bold tracking-tighter mt-2">Story about us</h1>
      </div>
      <div class="border-b-4 border-red-400 w-16 mx-auto my-8"></div>
      <p class="font-Roboto text-sm w-3/4 mx-auto mb-24 text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
        Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
    </div>
    <div class="container mx-auto grid grid-cols-1 md:grid-cols-3 justify-center mb-32">
      <div class="story-image grid justify-center p-5">
        <story-card>
          <img-loader name="card1" alt="computer"></img-loader>
          <div class="story-image-text">
            <img-loader class="pl-10" name="users" alt="users"></img-loader>
            <h3>Super Team</h3>
          </div>
        </story-card>
      </div>
      <div class="story-image grid justify-center p-5">
        <story-card>
          <img-loader name="card2" alt="table1"></img-loader>
          <div class="story-image-text">
            <img-loader class="pl-10" name="users" alt="users"></img-loader>
            <h3>Super Team</h3>
          </div>
        </story-card>
      </div>
      <div class="story-image grid justify-center p-5">
        <story-card>
          <img-loader name="card3" alt="table2"></img-loader>
          <div class="story-image-text">
            <img-loader class="pl-10" name="users" alt="users"></img-loader>
            <h3>Super Team</h3>
          </div>
        </story-card>
      </div>
    </div>
  </section>
</template>

<script>
import StoryCard from '~/components/StoryCard';
import ImgLoader from '~/components/ImgLoader';

export default {
  components: {
    StoryCard,
    ImgLoader
  }
};
</script>

<style>
.story-image-text {
  @apply hidden text-white uppercase font-bold font-Montserrat;
}

.story-image:hover .story-image-text {
  @apply block absolute z-50;
  top: 50%;
  left: 50%;
  margin-right: -50%;
  transform: translate(-50%, -50%)
}

</style>
