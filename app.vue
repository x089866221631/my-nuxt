<template>
  <NuxtLink to="/">首页</NuxtLink>|
  <NuxtLink to="/video">视频</NuxtLink>

  <!-- Nuxt路由页面 相当于RouterVie -->
  <NuxtPage />
</template>
<script setup lang="ts">
useSeoMeta({
  title: "nuxt测试",
  description: "这是我的神奇网站，让我告诉你关于它的一切。",
  keywords: "nuxt,测试,网站",
});
</script>
<style scoped></style>
