<script setup>
import { RouterLink } from 'vue-router';
</script>
<template>
    <section class="text-center flex flex-col justify-center items-center h-96">
      <i class="pi pi-exclamation-triangle text-yellow-500 text-7xl mb-5 custom-icon"></i>
      <h1 class="text-4xl font-bold mb-4">404 Not Found</h1>
      <p class="text-xl mb-5">This page does not exist</p>
      <RouterLink
        to="/"
        class="text-white bg-green-700 hover:bg-green-900 rounded-md px-3 py-2 mt-4"
        >Go Back</RouterLink
      >
    </section>
</template>
<style>
.custom-icon {
  color: rgb(247, 128, 30);
  font-size: 10rem; 
}
</style>