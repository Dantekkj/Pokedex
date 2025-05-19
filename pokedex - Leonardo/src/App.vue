<template>
  <div class="bg-gray-100 min-h-screen">
    <Navbar/>
    <div class="main container mx-auto px-4 py-6">
      <router-view/>
    </div>
  </div>
</template>

<script setup>
import Navbar from './components/NavbarComponent.vue'
import footer from './components/footerContent.vue'
</script>