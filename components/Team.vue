<template>
  <section>
    <div class="bg-white font-Montserrat container mx-auto text-center pt-20">
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
        <div class="story-image">
          <story-card>
            <img src="/team1.png" alt="team designer">
            <div class="story-image-text team-text">
              <team-social></team-social>
            </div>
          </story-card>
        </div>
        <h3 class="team-name">Metthew Dix</h3>
        <p class="team-position">Graphic Design</p>
      </div>
      <div>
        <div class="story-image">
          <story-card>
            <img src="/team2.png" alt="team Ui|Ux">
            <div class="story-image-text team-text">
              <team-social></team-social>
            </div>
          </story-card>
        </div>
        <h3 class="team-name">Christopher Campbell</h3>
        <p class="team-position">Branding/UX design</p>
      </div>
      <div>
        <div class="story-image">
          <story-card>
            <img src="/team3.png" alt="team developer">
            <div class="story-image-text team-text">
              <team-social></team-social>
            </div>
          </story-card>
        </div>
        <h3 class="team-name">Michael Fertig</h3>
        <p class="team-position">Developer</p>
      </div>
    </div>
  </section>
</template>

<script>
import StoryCard from '~/components/StoryCard';
import TeamSocial from '~/components/TeamSocial';

export default {
  components: {
    StoryCard,
    TeamSocial
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

.story-image:hover .team-text{
  left: 20%;
}

</style>
