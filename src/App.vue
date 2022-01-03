<template>
  <div style="height: calc(100vh - 7rem); padding: 1rem;">
  <div style="padding: 1rem 0;">
    iframe src:
    <input v-model="src">
  </div>

    <iframe style="height: 100%; width: 100%" :src="src" />
  </div>
</template>

<script lang="ts" setup>
import { ref } from 'vue'
const src = ref('https://localhost:3000')
</script>