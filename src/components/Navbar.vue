<script setup>
// Logika navbar nanti ditaruh di sini
</script>

<template>
  <nav class="w-full bg-white shadow-sm fixed top-0 left-0 z-50">
    <!-- Mengganti 'container' dengan 'max-w-5xl' agar lebih menyempit ke tengah -->
    <div class="max-w-5xl mx-auto px-6 py-4 flex justify-between items-center">
      
      <div class="text-2xl font-bold text-gray-800">
        Portofolio<span class="text-blue-600">.</span>
      </div>
      
      <ul class="flex gap-8 text-gray-600 font-medium">
        <li><a href="#" class="hover:text-blue-600 transition-colors">Home</a></li>
        <li><a href="#" class="hover:text-blue-600 transition-colors">Projects</a></li>
        <li><a href="#" class="hover:text-blue-600 transition-colors">About</a></li>
        <li><a href="#" class="hover:text-blue-600 transition-colors">Contact</a></li>
      </ul>
      
    </div>
  </nav>
</template>