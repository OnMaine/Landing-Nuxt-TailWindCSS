<template>
  <div>
    <Header />
    <main>
      <nuxt/>
    </main>
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/Header'
import Footer from '@/components/Footer'

export default {
  components: {
    Header,
    Footer
  }
};
</script>

<style>

::-webkit-scrollbar {
  @apply w-2 h-2 bg-gray-400;
}


::-webkit-scrollbar-thumb {
  @apply bg-teal-500 rounded-full shadow-inner;
}

::-webkit-scrollbar-thumb:hover {
  @apply bg-red-400;
}

::-webkit-scrollbar-button:vertical:start:decrement {
    background: linear-gradient(120deg, #fff5f7 40%, rgba(0, 0, 0, 0) 41%),
                linear-gradient(240deg, #fff5f7 40%, rgba(0, 0, 0, 0) 41%),
                linear-gradient(0deg, #fff5f7 30%, rgba(0, 0, 0, 0) 31%);
    @apply bg-teal-500;
}

::-webkit-scrollbar-button:vertical:end:increment {
    background:
        linear-gradient(300deg, #fff5f7 40%, rgba(0, 0, 0, 0) 41%),
        linear-gradient(60deg, #fff5f7 40%, rgba(0, 0, 0, 0) 41%),
        linear-gradient(180deg, #fff5f7 30%, rgba(0, 0, 0, 0) 31%);
    @apply bg-teal-500;
}

::-webkit-scrollbar-button:horizontal:start:decrement {
    background:
        linear-gradient(30deg, #fff5f7 40%, rgba(0, 0, 0, 0) 41%),
        linear-gradient(150deg, #fff5f7 40%, rgba(0, 0, 0, 0) 41%),
        linear-gradient(270deg, #fff5f7 30%, rgba(0, 0, 0, 0) 31%);
    @apply bg-teal-500;
}

::-webkit-scrollbar-button:horizontal:end:increment {
    background:
        linear-gradient(210deg, #fff5f7 40%, rgba(0, 0, 0, 0) 41%),
        linear-gradient(330deg, #fff5f7 40%, rgba(0, 0, 0, 0) 41%),
        linear-gradient(90deg, #fff5f7 30%, rgba(0, 0, 0, 0) 31%);
    @apply bg-teal-500;
}
</style>
