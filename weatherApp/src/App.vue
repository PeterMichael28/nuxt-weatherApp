<template>
  <div class="flex flex-col min-h-full font-Roboto bg-pry" >
    <Navigation />
    <RouterView />
  </div>
</template>

<script setup>
import { RouterView } from 'vue-router'
import Navigation from './components/Navigation.vue'
</script>
