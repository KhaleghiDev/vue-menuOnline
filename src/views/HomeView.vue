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
    align-items: flex-end;
    display: flex;
    flex-direction: column;
    align-content: center;
    justify-content: center;
    flex-wrap: nowrap;
}
}
</style>