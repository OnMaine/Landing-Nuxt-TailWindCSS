<template>
  <section>
    <div class="bg-white font-Montserrat container mx-auto text-center mt-24">
      <div>
        <span class="text-xl font-Kaushan">Service</span>
        <h1 class="uppercase text-2xl font-Montserrat font-bold tracking-tighter mt-2">what we do</h1>
      </div>
      <div class="border-b-4 border-red-400 w-16 mx-auto my-8"></div>
      <p class="font-Roboto text-sm w-3/4 mx-auto mb-24 text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
         Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. </p>
    </div>
    <div class="container mx-auto flex justify-around">
      <div class="w-1/2 pb-16">
        <img src="/photo.png" alt="what we do">
      </div>
      <div class="w-1/2">
        <ul class="list-none m-0 p-0">
          <presentation-tabs>
            <ptabs-icon name="PICTURE" alt="photo"> asd</ptabs-icon>
            <h1 tabindex="-1">Photography</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Enim optio commodi magni aliquam quas amet voluptatibus, et error vitae,
               repellendus unde minima fuga fugiat consequatur laboriosam aut nostrum molestias accusantium!

               Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
               Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
             </p>
          </presentation-tabs>
          <presentation-tabs>
            <ptabs-icon name="EQUALIZER" alt="creativ"> asd</ptabs-icon>
            <h1 tabindex="-1">Creativity</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Enim optio commodi magni aliquam quas amet voluptatibus, et error vitae, repellendus unde minima
               fuga fugiat consequatur laboriosam aut nostrum molestias accusantium!
               Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
               Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
               Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.
             </p>
          </presentation-tabs>
          <presentation-tabs>
            <ptabs-icon name="BULLSEYE" alt="design"> asd</ptabs-icon>
            <h1 tabindex="-1">Web design</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Enim optio commodi magni aliquam quas amet voluptatibus, et error vitae,
               repellendus unde minima fuga fugiat consequatur laboriosam aut nostrum molestias accusantium!

               Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
               Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
             </p>
          </presentation-tabs>
        </ul>
      </div>
    </div>
  </section>
</template>

<script>
import PresentationTabs from '~/components/PresentationTabs';
import PtabsIcon from '~/components/PtabsIcon';

export default {
  components: {
    PresentationTabs,
    PtabsIcon
  },
};
</script>

<style>

</style>
