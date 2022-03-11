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
  background-color: purple;
  border: 1px solid black;

  flex-grow: 1;
}
</style>
