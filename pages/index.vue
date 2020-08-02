<template>
  <div>
    <Hero/>
  </div>
</template>

<script>
import Hero from '@/components/Hero'

export default {
  components: {
    Hero
  }
};
</script>

<style scoped>
.badge {
  @apply inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700;
  &:hover {
    @apply bg-gray-300;
  }
}
</style>
