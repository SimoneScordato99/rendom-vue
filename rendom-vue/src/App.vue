<script setup>
import { store } from "./store.js";
import Header from './components/Header.vue';
</script>

<template>
  <section class="appp">
    <Header></Header>
  </section>
</template>

<style scoped>
  .appp{
    width: 100vw;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    height: 100vh;
  }
</style>
