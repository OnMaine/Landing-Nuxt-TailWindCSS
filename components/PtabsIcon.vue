<template>
  <img class="Ptabs-icon" :src="'/'+`${name}`+'.png'" />
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
.Ptabs-icon {
  @apply float-left p-3 pb-0;
}

</style>
