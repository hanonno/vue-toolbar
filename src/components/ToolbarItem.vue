<script setup>
import { ref } from 'vue';

defineProps({
  text: String,
});
</script>

<template>
  <div class="toolbar-item">{{ text }}</div>
</template>

<style scoped>
.toolbar-item {
  background-color: green;
  border: 1px solid black;
  padding: 4px;
}
</style>
