<template>
  <section>
    <div class="bg-white font-Montserrat container mx-auto text-center mt-20">
      <div>
        <span class="text-xl font-Kaushan">Who we are</span>
        <h1 class="uppercase text-2xl font-Montserrat font-bold tracking-tighter mt-2">Meet Our team</h1>
      </div>
      <div class="border-b-4 border-red-400 w-16 mx-auto my-8"></div>
      <p class="font-Roboto text-sm w-3/4 mx-auto mb-24 text-gray-600">
         Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
         labore et dolore magna aliqua.
         Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. </p>
    </div>
    <div class="container mx-auto flex flex-row justify-around mb-32 text-center">
      <div>
        <story-card>
          <img src="/team1.png" alt="team designer">
        </story-card>
        <h3 class="team-name">Metthew Dix</h3>
        <p class="team-position">Graphic Design</p>
      </div>
      <div>
        <story-card>
          <img src="/team2.png" alt="team Ui|Ux">
        </story-card>
        <h3 class="team-name">Christopher Campbell</h3>
        <p class="team-position">Branding/UX design</p>
      </div>
      <div>
        <story-card>
          <img src="/team3.png" alt="team developer">
        </story-card>
        <h3 class="team-name">Michael Fertig</h3>
        <p class="team-position">Developer</p>
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
.team-name {
  @apply uppercase text-xl font-Montserrat font-bold pt-10;
}

.team-position {
  @apply italic font-thin text-base;
}
</style>
