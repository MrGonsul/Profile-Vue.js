<script setup>
import { ref } from 'vue'
const name = ref('Mr Gonsul') 
</script>
<template>
  <header>
    <img src="/src/assets/logo_vue_300px.png" alt="logo_vue">
    <h1>Hi, I'm <span class="highlight">{{ name }}</span></h1>
    <p>Junior Vue Devoloper</p>
  </header>
</template>

<style scoped>

header img {
  height: 150px;
}

header h1 {
  font-size: 2rem;
  color: #34495e;
  margin-top: 10px;
}

header p {
  color: green;
  text-decoration: underline;
  font-weight: bold;
}

</style>
