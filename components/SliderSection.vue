<template>
  <hooper style="height: 230px" :settings="hooperSettings" class="slider">
    <slide class="slide">
      <img-loader class="slide-img" name="user" alt="design"> asd</img-loader>
      <blockquote>
        <p class="block-text">
          “Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
           Ut enim ad minim veniam, quis nostrud exercitation.”
        </p>
        <div class="relative">
          <p class="block-signature">Jon Doe</p>
        </div>
      </blockquote>
    </slide>
    <slide class="slide">
      <img-loader class="slide-img" name="user2" alt="design"> asd</img-loader>
      <blockquote>
        <p class="block-text">
          “Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
           Ut enim ad minim veniam, quis nostrud exercitation.”
        </p>
        <div class="relative">
          <p class="block-signature">Joshua Earle</p>
        </div>
      </blockquote>
    </slide>
    <hooper-navigation class="hooper-navigation" slot="hooper-addons"></hooper-navigation>
  </hooper>
</template>

<script>
import {
  Hooper,
  Slide,
  Navigation as HooperNavigation
} from 'hooper';
import ImgLoader from '~/components/ImgLoader';
import 'hooper/dist/hooper.css';

export default {
  name: 'App',
  components: {
    Hooper,
    Slide,
    HooperNavigation,
    ImgLoader
  },
  data() {
    return {
      hooperSettings: {
        itemsToShow: 1,
        centerMode: true,
        infiniteScroll: true,
        centerMode: true,
        autoPlay: true,
        playSpeed: 5000,
        transition: 1000
      }
    };
  }
};
</script>

<style>
.slider {
   @apply bg-gray-300 h-full hidden;
   @screen lg {
     @apply block;
   }
}

.slide-img {
  @apply mx-24 float-left pb-0 p-3;
}
.slide {
  @apply my-10;
}

.block-text {
  @apply font-Roboto italic w-4/5 pt-10;
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

.block-signature {
  &::before {
  @apply border-b-4 border-red-400 w-32 absolute;
  content: "";
  top: 100%;
 }
}
</style>
