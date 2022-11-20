<script setup lang="ts">
import Header from "@/components/header.vue";
</script>

<template>
  <img style="width: 100%" src="/assets/px-image-4.jpg" alt="" />
  <Header />
  <router-view />
</template>

<style lang="scss">
@import "@/scss/style.scss";
@import "@/scss/variable.scss";
</style>
