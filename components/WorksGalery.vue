<template>
  <div class="grid grid-cols-4 gap-0">
    <div class="works-content">
      <works-img name="work"></works-img>
      <works-text></works-text>
    </div>
    <div class="works-content">
      <works-img name="work3"></works-img>
      <works-text></works-text>
    </div>
    <div class="works-content row-span-2">
      <works-img name="work5" ></works-img>
      <works-text></works-text>
    </div>
    <div class="works-content">
      <works-img name="work7"></works-img>
      <works-text></works-text>
    </div>
    <div class="works-content">
      <works-img name="work2"></works-img>
      <works-text></works-text>
    </div>
    <div class="works-content">
      <works-img name="work4"></works-img>
      <works-text></works-text>
    </div>
    <div class="works-content">
      <works-img name="work6"></works-img>
      <works-text></works-text>
    </div>
  </div>
</template>

<script>
import WorksImg from '~/components/WorksImg';
import WorksText from '~/components/WorksText';

export default {
  components: {
    WorksImg,
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
