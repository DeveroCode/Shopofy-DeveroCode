<script setup>
import Header from './components/Header.vue';
import Main from './components/Main.vue'
import Launch from './components/Launch.vue';
import Join_us from './components/Join_us.vue'
import Footer from './components/Footer.vue';
</script>

<template>
  <div class="max-w-full">
    <Header />
    <div class="max-w-7xl mx-auto">
      <Main />
    </div>
    <Launch />
    <div class="max-w-7xl mx-auto">
      <Join_us />
    </div>

    <Footer />
  </div>
</template>