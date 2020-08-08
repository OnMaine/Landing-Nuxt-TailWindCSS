<template>
  <div class="grid grid-cols-4 gap-0">
    <div class="works-content">
      <img-loader name="work"></img-loader>
      <works-text></works-text>
    </div>
    <div class="works-content">
      <img-loader name="work3"></img-loader>
      <works-text></works-text>
    </div>
    <div class="works-content row-span-2">
      <img-loader name="work5" ></img-loader>
      <works-text></works-text>
    </div>
    <div class="works-content">
      <img-loader name="work7"></img-loader>
      <works-text></works-text>
    </div>
    <div class="works-content">
      <img-loader name="work2"></img-loader>
      <works-text></works-text>
    </div>
    <div class="works-content">
      <img-loader name="work4"></img-loader>
      <works-text></works-text>
    </div>
    <div class="works-content">
      <img-loader name="work6"></img-loader>
      <works-text></works-text>
    </div>
  </div>
</template>

<script>
import ImgLoader from '~/components/ImgLoader';
import WorksText from '~/components/WorksText';

export default {
  components: {
    ImgLoader,
    WorksText
  }
};
</script>

<style>
.works-content {
  @apply relative z-0;
  &:hover {
    @apply cursor-pointer;
    &::before {
      @apply absolute w-full h-full z-10 flex;
       content: "";
       background: linear-gradient(#db7474, #e3cc7c);
       opacity: 0.9;
    }
  }
}
</style>
