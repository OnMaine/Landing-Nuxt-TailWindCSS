<template>
  <nav>
    <div class="container mx-auto px-6 py-2 flex justify-between items-center">
      <a class="font-bold xt-2xl lg:text-3xl" href="#">
        MoGo
      </a>
      <div class="block lg:hidden">
        <button class="flex items-center px-3 py-2 border rounded text-white border-gray-100 hover:text-gray-100 hover:border-teal-500 appearance-none focus:outline-none">
          <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
            <title>Menu</title>
            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
          </svg>
        </button>
      </div>
      <div class="hidden lg:block">
        <ul class="inline-flex">
          <li><a class="link" href="#">About</a></li>
          <li><a class="link" href="#">Service</a></li>
          <li><a class="link" href="#">Work</a></li>
          <li><a class="link" href="#">Blog</a></li>
          <li><a class="link" href="#">Contact</a></li>
          <li><a class="link-img" href="#">
              <svg class="inline-flex" width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" stroke="currentColor">
                <path d="M3 3H5L5.4 5M7 13H17L21 5H5.4M7 13L5.4 5M7 13L4.70711 15.2929C4.07714 15.9229 4.52331 17 5.41421 17H17M17 17C15.8954 17 15 17.8954 15 19C15 20.1046 15.8954 21 17 21C18.1046 21 19 20.1046 19 19C19 17.8954 18.1046 17 17 17ZM9 19C9 20.1046 8.10457 21 7 21C5.89543 21 5 20.1046 5 19C5 17.8954 5.89543 17 7 17C8.10457 17 9 17.8954 9 19Z"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"/>
              </svg>
            </a>
          </li>
          <li>
            <a class="link-img" href="#">
              <svg class="inline-flex" width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" stroke="currentColor">
                <path d="M21 21L15 15M17 10C17 13.866 13.866 17 10 17C6.13401 17 3 13.866 3 10C3 6.13401 6.13401 3 10 3C13.866 3 17 6.13401 17 10Z"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"/>
              </svg>
            </a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {

}

</script>

<style>
.logo {

}
.link {
  @apply px-6 text-white uppercase;
  &:hover {
    @apply text-orange-300 font-bold border-b-2 border-solid border-orange-300;
  }
  &:focus {
    @apply text-orange-300 font-bold border-b-2 border-solid border-orange-300;
  }
}
.link-img {
  @apply text-white px-4;
  &:hover {
    @apply text-orange-300;
  }
}
</style>
