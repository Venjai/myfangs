<template>
  <Header />
  <router-view></router-view>
  <Footer />
</template>

<script setup lang="ts">
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Babylonica&family=Cinzel+Decorative:wght@400;700;900&family=Marcellus+SC&display=swap');
</style>
