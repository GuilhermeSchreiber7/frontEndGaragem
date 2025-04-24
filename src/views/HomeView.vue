<script setup>
import garagemHeader from '@/components/garagemHeader.vue';
</script>

<template>
  <div class="app">
    <garagemHeader/>
    <RouterView />
  </div>
</template>
<style scoped>
  .app{
    height: 100vh;
    width: 100vw;

    background-color: rgb(56, 56, 56)
  }
  </style>
