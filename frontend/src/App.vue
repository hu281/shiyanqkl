<template>
  <div class="app-container">
    <Blocklist />
  </div>
</template>

<script setup>
import Blocklist from './components/Blocklist.vue';
</script>

<style scoped>
.app-container {
  min-height: 100vh;
  background-color: #f8f9fa;
  padding: 20px;
}
</style>