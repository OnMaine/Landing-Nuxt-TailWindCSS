<template>
<nuxt />
</template>

<script>
export default {
  head: {
    title: "Nuxt.js with TailwindCSS",
    meta: [{
        charset: "utf-8"
      },
      {
        name: "viewport",
        content: "width=device-width, initial-scale=1"
      },
      {
        hid: "description",
        name: "description",
        content: "Nuxt.js with TailwindCSS example"
      }
    ],
    link: [{
      rel: "icon",
      type: "image/x-icon",
      href: "/favicon.ico"
    }],
    link: [{
      rel: "stylesheet",
      href:"https://fonts.googleapis.com/css2?family=Kaushan+Script&family=Montserrat:wght@400;700&family=Roboto:wght@400;700&display=swap"
    }],
  }
};
</script>

<style>
/* полоса прокрутки (скроллбар) */
::-webkit-scrollbar {
  @apply w-2 h-2 bg-gray-400;
}

/* ползунок скроллбара */
::-webkit-scrollbar-thumb {
  @apply bg-teal-500 rounded-full shadow-inner;
}

::-webkit-scrollbar-thumb:hover {
  @apply bg-red-400;
}

/* Стрелки */

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
