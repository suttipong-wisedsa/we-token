<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import Nav from './components/Nav.vue'
import Content from './components/Content.vue';
</script>

<template>
  <header>
    <div class="wrapper">
      <Nav />
      <Content />    
    </div>
  </header>
</template>

<style scoped>
body{
  margin: 0;
}
</style>
