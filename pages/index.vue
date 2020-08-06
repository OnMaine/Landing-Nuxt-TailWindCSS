<template>
  <div>
    <Hero />
    <Story />
    <Stats />
    <Services />
    <Mobile />
    <Presentation />
    <Slider />
    <Team />
    <Hipster />

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
import Team from '@/components/Team'
import Hipster from '@/components/Hipster'

export default {
  components: {
    Hero,
    Story,
    Stats,
    Services,
    Mobile,
    Presentation,
    Slider,
    Team,
    Hipster
  }
};
</script>

<style>

</style>
