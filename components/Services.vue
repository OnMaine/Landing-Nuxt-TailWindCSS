<template>
  <section>
    <div class="bg-white container mx-auto text-center py-20">
      <div>
        <span class="text-xl font-Kaushan">We work with</span>
        <h1 class="uppercase text-2xl font-Montserrat font-bold tracking-tighter mt-2">Amazing Services</h1>
      </div>
      <div class="border-b-4 border-red-400 w-16 mx-auto my-8"></div>
    </div>
    <div class="container mx-auto mb-32">
      <div class="services-cards grid grid-cols-1 my-10 md:grid-cols-3">
        <div class="services-card">
          <img class="services-img" src="~assets/img/alarm.svg" alt="Photography">
          <div>
            <h4>Photography</h4>
            <p class="font-Roboto">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
          </div>
        </div>
        <div class="services-card">
          <img class="services-img" src="~assets/img/line.svg" alt="Web Design">
          <div>
            <h4>Web Design</h4>
            <p class="font-Roboto">Ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
          </div>
        </div>
        <div class="services-card">
          <img class="services-img" src="~assets/img/computer.svg" alt="Creativity">
          <div>
            <h4>Creativity</h4>
            <p class="font-Roboto">Dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
          </div>
        </div>
      </div>
      <hr>
      <div class="services-cards grid grid-cols-1 my-10 md:grid-cols-3">
        <div class="services-card">
          <img class="services-img" src="~assets/img/book.svg" alt="Seo">
          <div>
            <h4>Seo</h4>
            <p class="font-Roboto">Ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod.</p>
          </div>
        </div>
        <div class="services-card">
          <img class="services-img" src="~assets/img/home.svg" alt="CSS/HTML">
          <div>
            <h4>CSS/HTML</h4>
            <p class="font-Roboto">Lorem dolor sit amet, consectetur adipiscing elit, sed do tempor.</p>
          </div>
        </div>
        <div class="services-card">
          <img class="services-img" src="~assets/img/image.svg" alt="Digital">
          <div>
            <h4>Digital</h4>
            <p class="font-Roboto">Sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>

</script>

<style>

.services-card {
  @apply flex items-start p-5;
  & h4 {
    @apply font-bold font-Montserrat text-gray-900 text-sm;
  }
  & p {
    @apply font-Roboto pt-2 pr-10 text-gray-600 text-sm;
  }
}

.services-img {
  @apply pr-5;
}

</style>
