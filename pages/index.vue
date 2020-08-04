<template>
  <div>
    <Hero/>
    <Story/>
    <Stats/>
    <Services/>
    <Mobile/>
    <Presentation/>
    <slider/>

  </div>
</template>

<script>
import Hero from '@/components/Hero'
import Story from '@/components/Story'
import Stats from '@/components/Stats'
import Services from '@/components/Services'
import Mobile from '@/components/Mobile'
import Presentation from '@/components/Presentation'
import Slider from '@/components/Slider'

export default {
  components: {
    Hero,
    Story,
    Stats,
    Services,
    Mobile,
    Presentation,
    Slider
  }
};
</script>

<style>

</style>
