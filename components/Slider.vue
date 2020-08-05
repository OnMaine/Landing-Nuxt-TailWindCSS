<template>
  <hooper :settings="hooperSettings" class="slider-section">
    <slide class="slide">
      <ptabs-icon class="slide-img" name="group" alt="design"> asd</ptabs-icon>
      <blockquote>
        <p class="block-text">
          “Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
           Ut enim ad minim veniam, quis nostrud exercitation.”
        </p>
        <p class="block-signature">Jon Doe</p>
      </blockquote>
    </slide>
    <slide class="slide">
      <ptabs-icon class="slide-img" name="user" alt="design"> asd</ptabs-icon>
      <blockquote>
        <p class="block-text">
          “Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
           Ut enim ad minim veniam, quis nostrud exercitation.”
        </p>
        <p class="block-signature">Joshua Earle</p>
      </blockquote>
    </slide>
    <hooper-navigation class="hooper-navigation" slot="hooper-addons"></hooper-navigation>
    <hooper-pagination class="hooper-navigation"  slot="hooper-addons"></hooper-pagination>
  </hooper>
</template>

<script>
import {
  Hooper,
  Slide,
  Navigation as HooperNavigation
} from 'hooper';
import PtabsIcon from '~/components/PtabsIcon';
import 'hooper/dist/hooper.css';

export default {
  name: 'App',
  components: {
    Hooper,
    Slide,
    HooperNavigation,
    PtabsIcon
  },
  data() {
    return {
      hooperSettings: {
        itemsToShow: 1,
        centerMode: true
      }
    };
  }
};
</script>

<style>
.slider-section {
   @apply bg-gray-300 mb-24 h-full;
}

.slide-img {
  @apply mx-24 pb-0;
}
.slide {
  @apply my-10 self-center;
}

.block-text {
  @apply font-Roboto italic w-4/5;
}

.block-signature {
  @apply text-4xl font-Kaushan;
}

.hooper-list {
  width: 100%;
  max-width: 1280px;
  margin-right: auto;
  margin-left: auto;
}


</style>
