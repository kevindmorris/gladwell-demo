<template>
  <main>
    <div>{{ demo }}</div>
    <div>{{ demoUpper }}</div>
    <div>{{ demoLower }}</div>
    <div>{{ demoSnake }}</div>
    <div>{{ demoKebab }}</div>
  </main>
</template>

<script setup lang="ts">
import gladwell from "gladwell";

const demo = "Hello, World!";

const demoUpper = gladwell.upper(demo);
const demoLower = gladwell.lower(demo);
const demoSnake = gladwell.snake(demo);
const demoKebab = gladwell.kebab(demo);
</script>

<style scoped></style>
