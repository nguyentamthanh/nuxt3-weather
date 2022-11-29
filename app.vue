<template>
  <NuxtLayout :name="layout">
    <NuxtPage />
  </NuxtLayout>
</template>
<script setup>
useHead({
  title: "Weather App",
  link: [
    {
      rel: "icon",
      type: "image/png",
      href: "/nuxt.png",
    },
  ],
});
</script>
