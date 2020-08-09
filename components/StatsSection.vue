<template>
  <section class="bg-teal-300">
    <div class="container mx-auto grid grid-cols-2 sm:grid-cols-5">
      <stats-card>
        <h3 class="font-bold text-6xl">42</h3>
        <p class="text-sm">Web Design Projects</p>
      </stats-card>
      <stats-card>
        <h3 class="font-bold text-6xl">123</h3>
        <p class="text-sm">Happy Client</p>
      </stats-card>
      <stats-card>
        <h3 class="font-bold text-6xl">15</h3>
        <p class="text-sm">Award Winner</p>
      </stats-card>
      <stats-card>
        <h3 class="font-bold text-6xl">99</h3>
        <p class="text-sm">Cup of Coffee</p>
      </stats-card>
      <stats-card>
        <h3 class="font-bold text-6xl">24</h3>
        <p class="text-sm">Members</p>
      </stats-card>
    </div>
  </section>
</template>

<script>
import StatsCard from '~/components/StatsCard';

export default {
  components: {
    StatsCard,
  }
};
</script>

<style>

</style>
