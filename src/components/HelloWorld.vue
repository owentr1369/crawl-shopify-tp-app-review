<script setup lang="ts">
import { ref } from "vue";

defineProps<{ msg: string }>();

const count = ref(0);
</script>

<template>
  <h1>Hello this is my Vite Vue Chrome Extension</h1>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
