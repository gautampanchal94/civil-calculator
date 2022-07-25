<script setup>
// import { RouterLink, RouterView } from 'vue-router'

import NavBar from '@/components/NavBar.vue'
import FooterItem from '@/components/FooterItem.vue';

</script>

<template>
  <header>
    <h1 class="py-3 text-center text-3xl font-bold text-slate-600">Civil Calculator</h1>
    <NavBar></NavBar>
  </header>

  <RouterView/>
  
  <FooterItem></FooterItem>
</template>

<style>

</style>
