<template>
  <div class="relative bg-[url('./assets/images/bodybackground.jpg')] bg-[length:70rem] bg-center w-full h-[100vh]">
    <home v-if="page === 0"></home>
    <secndpage v-if="page === 1"></secndpage>
    <button @click="page ++">yo</button>
  </div>
</template>

<script setup>

import { ref } from 'vue'
import home from './components/home.vue'
import secndpage from './components/2ndpage.vue'

const page = ref(0)
</script>

<style scoped>
</style>
