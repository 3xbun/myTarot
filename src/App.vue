<template>
  <div>
    <Hero />
    <div class="container">
      <CoD />
      <Contents />
    </div>
    <Footer />
  </div>
</template>

<script setup>
import Hero from './components/Hero.vue';
import Footer from './components/Footer.vue';
import Contents from './components/Contents.vue';
import CoD from './components/CoD.vue';
import Card from './components/Card.vue';
</script>

<style scoped></style>