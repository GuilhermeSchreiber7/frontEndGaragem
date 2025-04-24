<script setup>
import garagemHeader from '@/components/garagemHeader.vue';
</script>

<template>
  <div class="app">
    <garagemHeader/>
    <div class="content">
      Garagem
    </div>
  </div>
</template>
<style scoped>
  .app{
    height: 100vh;
    width: 100vw;
    background-color: rgb(56, 56, 56)
  }
  .content {
   width: 100%;
    height: 90vh;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    font-size: 10rem;
  }
  </style>
