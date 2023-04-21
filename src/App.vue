<script setup>
import { RouterLink, RouterView } from 'vue-router'
import NavbarMenu from './components/NavbarMenu.vue'
import FooterMenu from './components/FooterMenu.vue'
</script>

<template>
  <NavbarMenu />
  <RouterView />
  <!-- <FooterMenu /> -->
</template>

