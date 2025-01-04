<script setup lang="ts">
import { RouterLink, RouterView, useRouter } from 'vue-router'
import homeView from '@/pages/homeView.vue'

</script>


<template>
  <v-app>
    <v-layout>
      <homeView />
      
      <RouterLink to="/">
      </RouterLink>
    </v-layout>
  </v-app>
</template>


<style scoped>
</style>
