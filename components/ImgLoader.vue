<template>
    <img :src="require(`@/assets/img/`+`${name}`+`.png`)" >
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
