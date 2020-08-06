<template>
  <div class="grid grid-cols-4 gap-0">
  <works-img name="work" alt="work"></works-img>
  <works-img name="work3" alt="work"></works-img>
  <works-img class="row-span-2" name="work5" alt="work"></works-img>
  <works-img name="work7" alt="work"></works-img>
  <works-img name="work2" alt="work"></works-img>
  <works-img name="work4" alt="work"></works-img>
  <works-img name="work6" alt="work"></works-img>
  </div>
</template>

<script>
import WorksImg from '~/components/WorksImg';

export default {
  components: {
    WorksImg
  }
};
</script>

<style>

</style>
