<template>
  <SidebarComponent />

  <RouterView />
</template>

<script setup>
  import { RouterLink, RouterView } from 'vue-router'
  import SidebarComponent from './components/sidebar/SidebarComponent.vue';
</script>