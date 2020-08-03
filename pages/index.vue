<template>
  <div>
    <Hero/>
    <Story/>
    <Stats/>
    <Services/>
    <Mobile/>
    <Presentation/>

  </div>
</template>

<script>
import Hero from '@/components/Hero'
import Story from '@/components/Story'
import Stats from '@/components/Stats'
import Services from '@/components/Services'
import Mobile from '@/components/Mobile'
import Presentation from '@/components/Presentation'

export default {
  components: {
    Hero,
    Story,
    Stats,
    Services,
    Mobile,
    Presentation
  }
};
</script>

<style>

</style>
