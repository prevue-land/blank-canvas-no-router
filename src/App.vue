<script setup lang="ts">
const currentYear = new Date().getFullYear();
</script>

<template>
  <main>
    <h1>blank-canvas-no-router</h1>
    <span>
      &copy; {{ currentYear }} Weekly OverVue. Released under MIT License
    </span>
  </main>
</template>

<style>
html,
body,
#app {
  width: 100vw;
  height: 100vh;
}

body {
  margin: 0;
  padding: 0;
  font-family: Arial, Helvetica, sans-serif;
}

main {
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>
