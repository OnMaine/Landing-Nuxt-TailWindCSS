<template>
  <section id="contacts" class="bg-custom-gr">
    <div class="container mx-auto">
      <div class="grid grid-cols-1 sm:grid-cols-3 pt-12">
        <div class="contacts-mogo p-5 grid grid-cols-1 grid-rows-2">
          <div>
            <h2 class="font-Montserrat text-5xl font-bold text-gray-500 pb-2">MoGo</h2>
            <p class="font-Montserrat text-sm text-gray-500 pb-5">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
               incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
               ullamco laboris nisi ut aliquip ex ea commodo consequat. </p>
          </div>
          <div>
            <p class="pb-3 border-gray-600 border-b"><span class="font-bold">15K</span> followers</p>
            <div class="pt-3 italic text-gray-500 flex">
              <span class="text-sm sm:text-base">Follow Us:</span>
              <div class="folow grid grid-cols-8 pl-5">
                <img-loader name="fb"></img-loader>
                <img-loader name="tw"></img-loader>
                <img-loader name="in"></img-loader>
                <img-loader name="gp"></img-loader>
                <img-loader name="yt"></img-loader>
                <img-loader name="dr"></img-loader>
                <img-loader name="tu"></img-loader>
                <img-loader name="pi"></img-loader>
              </div>
            </div>
            <div>
              <form class="contacts-form pt-5 grid grid-cols-2" action="#" method="post">
                <input class="p-1" type="email" id="email" placeholder="Your Email..." size="30">
                <button class="contacts-btn">Subscribe</button>
              </form>
            </div>
          </div>
        </div>
        <div class="contacts-blogs p-5">
          <h3 class="uppercase font-Montserrat font-bold text-sm pb-5">Blogs</h3>
          <div>
            <div class="contacts-blog-card">
              <img-loader name="soc1"></img-loader>
              <div class="contacts-blog-text">
                <h3>Lorem ipsum dolor sit amet,
                   consectetur adipiscing</h3>
                <p>Jan 9, 2016</p>
              </div>
            </div>
            <div class="contacts-blog-card">
              <img-loader name="soc2"></img-loader>
              <div class="contacts-blog-text">
                <h3>Consectetur adipiscing elit,
                   sed do eiusmod tempor</h3>
                <p>Jan 9, 2016</p>
              </div>
            </div>
            <div class="contacts-blog-card">
              <img-loader name="soc3"></img-loader>
              <div class="contacts-blog-text">
                <h3>sed do eiusmod tempor
                   incididunt ut labore</h3>
                <p>Jan 9, 2016</p>
              </div>
            </div>
          </div>
        </div>
        <div class="contacts-instagram p-5">
          <h3 class="uppercase font-Montserrat font-bold text-sm pb-5">Instagram</h3>
          <div class="instagram-images grid grid-cols-3">
            <img-loader name="inst1"></img-loader>
            <img-loader name="inst2"></img-loader>
            <img-loader name="inst3"></img-loader>
            <img-loader name="inst4"></img-loader>
            <img-loader name="inst5"></img-loader>
            <img-loader name="inst6"></img-loader>
            <img-loader name="inst7"></img-loader>
            <img-loader name="inst8"></img-loader>
            <img-loader name="inst9"></img-loader>
          </div>
          <p class="text-gray-500 italic text-xs pt-5">View more photos</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import ImgLoader from '~/components/ImgLoader';

export default {
  components: {
    ImgLoader
  }
};
</script>

<style>
.folow img {
  @apply pr-4 pt-1;
  &:hover {
    @apply cursor-pointer;
  }
}

.contacts-blog-card {
  @apply grid grid-cols-2 align-middle justify-center pr-2;
}

.contacts-blog-card img {
  @apply pb-5 pr-5;
  &:hover {
    @apply cursor-pointer;
  }
}

.contacts-blog-text h3 {
  @apply font-Montserrat font-bold uppercase text-xs whitespace-pre-line;
}

.contacts-blog-text p {
  @apply font-Montserrat text-xs text-gray-500 italic;
}

.contacts-btn {
  @apply bg-teal-300 text-white uppercase font-bold text-sm outline-none;
  &:hover {
    @apply cursor-pointer bg-white text-teal-300 border-2 border-teal-300;
  }
}

.instagram-images {
  max-width: 260px;
}

.instagram-images:hover {
  @apply cursor-pointer;
}

</style>
