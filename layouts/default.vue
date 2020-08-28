<template>
  <div>
    <TheHeader />
    <nuxt class="mx-auto p-4" />
  </div>
</template>

<script>
import TheHeader from "~/components/TheHeader";
export default {
  components: {
    TheHeader,
  },
  head: {
    title: "Nuxt.js with TailwindCSS",
    meta: [
      { charset: "utf-8" },
      { name: "viewport", content: "width=device-width, initial-scale=1" },
      {
        hid: "description",
        name: "description",
        content: "Nuxt.js with TailwindCSS example",
      },
    ],
    link: [{ rel: "icon", type: "image/x-icon", href: "/favicon.ico" }],
  },
};
</script>