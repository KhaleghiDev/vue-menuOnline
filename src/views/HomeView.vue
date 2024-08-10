<script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main>
    <TheWelcome />
  </main>
</template>
<style>
@media (min-width: 1024px) {
  main {
    min-height: 100vh;
    align-items: stretch;
    display: flex;
    flex-direction: column;
    flex-wrap: nowrap;
    align-content: space-between;
    justify-content: center;
}
}
</style>