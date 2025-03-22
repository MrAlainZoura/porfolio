<script setup>
import { RouterView } from 'vue-router';
import Header from './components/Header.vue';
</script>

<template>
  <header >
    <Header/>
  </header>

  <main class="bg-gray-900">
    <RouterView/>
  </main>

  <footer>

  </footer>
</template>

<style scoped>


</style>
