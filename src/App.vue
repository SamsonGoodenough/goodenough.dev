<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Construction from './components/Construction.vue'
</script>

<template>
  <div class="hero">
    <Construction />

    <!-- <nav>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
    </nav> -->
  </div>

  <!-- <RouterView /> -->
</template>

<style lang="scss">
@import "./assets/style.scss";
</style>