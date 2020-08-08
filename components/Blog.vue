<template>
  <section>
    <div class="container font-Montserrat mx-auto text-center py-20">
      <div>
        <span class="text-xl font-Kaushan">Our Stories</span>
        <h1 class="uppercase text-2xl font-Montserrat font-bold tracking-tighter mt-2">Latest Blog</h1>
      </div>
      <div class="border-b-4 border-red-400 w-16 mx-auto my-8"></div>
    </div>
    <div class="container mx-auto grid grid-cols-1 sm:grid-cols-3 gap-0 mb-32">
      <div class="blog-card">
        <div class="grid justify-center">
          <img-loader name="blog1"></img-loader>
        </div>
        <div class="blog-text">
          <h3>Lorem ipsum dolor sit amet</h3>
          <p>Consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna.</p>
          <blog-comments>
              <blog-stats>
                <img-loader name="view"></img-loader>
                <span>992</span>
              </blog-stats>
              <blog-stats>
                <img-loader name="com"></img-loader>
                <span>42</span>
              </blog-stats>
            </blog-comments>
        </div>
      </div>
      <div class="blog-card">
        <div class="grid justify-center">
          <img-loader name="blog2"></img-loader>
        </div>
        <div class="blog-text">
          <h3>sed do eiusmod tempor</h3>
          <p>Adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <blog-comments>
              <blog-stats>
                <img-loader name="view"></img-loader>
                <span>1560</span>
              </blog-stats>
              <blog-stats>
                <img-loader name="com"></img-loader>
                <span>98</span>
              </blog-stats>
            </blog-comments>
        </div>
      </div>
      <div class="blog-card">
        <div class="grid justify-center">
          <img-loader name="blog3"></img-loader>
        </div>
        <div class="blog-text">
          <h3>incididunt ut labore et dolore</h3>
          <p>Elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <blog-comments>
              <blog-stats>
                <img-loader name="view"></img-loader>
                <span>542</span>
              </blog-stats>
              <blog-stats>
                <img-loader name="com"></img-loader>
                <span>17</span>
              </blog-stats>
            </blog-comments>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import ImgLoader from '~/components/ImgLoader';
import BlogComments from '~/components/BlogComments';
import BlogStats from '~/components/BlogStats';

export default {
components: {
  ImgLoader,
  BlogComments,
  BlogStats
}
};
</script>

<style>
.blog-card {
  @apply grid grid-rows-2 justify-center px-3;
}

.blog-text {
  @apply row-span-2 grid justify-center mb-5;
}

.blog-text h3 {
  @apply font-Montserrat text-black font-bold uppercase text-lg py-4;
}

.blog-text p {
  @apply text-gray-500 border-gray-600 border-b;
  max-width: 380px;
}
</style>
