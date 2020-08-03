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
