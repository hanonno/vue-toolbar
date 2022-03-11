<script setup>
import { ref } from 'vue';

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <div class="toolbar"><slot /></div>
</template>

<style scoped>
.toolbar {
  background-color: red;
  padding: 8px;
}
</style>
