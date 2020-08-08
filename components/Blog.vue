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
        <img-loader name="blog1"></img-loader>
        <div class="blog-text">
          <h3>Lorem ipsum dolor sit amet</h3>
          <p>Consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <div class="line"></div>
          <div class="coments-stats">
            <img-loader name="view"></img-loader>
            <span>992</span>
            <img-loader name="com"></img-loader>
            <span>42</span>
          </div>
        </div>
      </div>
      <div class="blog-card">
        <img-loader name="blog2"></img-loader>
        <div class="blog-text">
          <h3>sed do eiusmod tempor</h3>
          <p>Adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <div class="line"></div>
          <div class="coments-stats">
            <img-loader name="view"></img-loader>
            <span>1560</span>
            <img-loader name="com"></img-loader>
            <span>98</span>
          </div>
        </div>
      </div>
      <div class="blog-card">
        <img-loader name="blog3"></img-loader>
        <div class="blog-text">
          <h3>incididunt ut labore et dolore</h3>
          <p>Elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          <div class="line"></div>
          <div class="coments-stats">
            <img-loader name="view"></img-loader>
            <span>542</span>
            <img-loader name="com"></img-loader>
            <span>17</span>
          </div>
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
.blog-card {
  @apply grid grid-rows-2 justify-center;
}

.blog-text {
  @apply row-span-2;
}

.blog-text h3 {
  @apply font-Montserrat text-black font-bold uppercase text-lg py-4;
}

.blog-text p {
  @apply text-gray-500  pr-10 pb-8;
}

.coments-stats {
  @apply flex flex-row py-3;

}

.coments-stats img{
  @apply py-2 pr-3;
}

.coments-stats span {
  @apply pr-5 text-sm self-center italic text-gray-600;
  &:hover {
    @apply underline cursor-pointer text-orange-400;
  }
}

.line {
  @apply bg-gray-600 border-b;
  max-width: 380px;
}
</style>
