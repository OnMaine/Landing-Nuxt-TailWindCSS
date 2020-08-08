<template>
    <img :src="'/'+`${name}`+'.png'" >
</template>

<script>
  export default {
      props: {
          name: {
              type: String,
              required: true
          }
      }
  }

</script>

<style>

</style>
