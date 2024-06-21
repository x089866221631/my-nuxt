<template>
  <h2>首页</h2>
  <van-button type="primary" @click="showToast('toast')">button</van-button>
  <VanButton type="success" @click="showNotify('notify')">button</VanButton>
  <LazyVanButton type="default">lazy button</LazyVanButton>
</template>

<script setup lang="ts"></script>

<style scoped></style>
