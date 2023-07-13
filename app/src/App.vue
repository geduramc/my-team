<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <video playsinline autoplay muted loop>
    <!-- <source src="../assets/background.webm" type="video/webm"> -->
    <source src="./assets/background.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <div class="overlay"></div>
  <RouterView />
  <footer>
    <a href="https://geduramc.com" target="_blank">By @geduramc &#9749;</a>
  </footer>
</template>

<style scoped>
</style>
