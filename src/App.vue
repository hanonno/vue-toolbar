<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue';
import Toolbar from './components/Toolbar.vue';
import ToolbarItem from './components/ToolbarItem.vue';
import ToolbarItemFlex from './components/ToolbarItemFlex.vue';
</script>

<template>
  <Toolbar>
    <ToolbarItem text="Export" />
    <ToolbarItemFlex />
    <ToolbarItem text="Add user" />
    <ToolbarItem text="Add partner" />
  </Toolbar>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
