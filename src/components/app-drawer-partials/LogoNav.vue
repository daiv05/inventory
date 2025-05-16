<template>
  <div class="logo">
    <RouterLink to="/inicio">
      <img :src="library" width="90%" alt="logo" />
    </RouterLink>
  </div>
</template>
<script setup>
import { RouterLink } from 'vue-router'
import library from '@/assets/icons/library.png'
</script>
