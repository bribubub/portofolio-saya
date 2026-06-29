<script setup>
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'
</script>

<template>
  <div class="min-h-screen bg-gray-50 pt-20"> 
    <Navbar />
    
    <main class="container mx-auto px-6">
      <Hero />
    </main>
  </div>
</template>