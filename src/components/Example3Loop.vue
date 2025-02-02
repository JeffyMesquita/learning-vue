<!-- Script -->
<script setup>
// Vector
let names = ["Ana", "Maria", "José", "Carlos", "Pedro"];
</script>

<!-- HTML -->
<template>
  <ul>
    <li v-for="name in names" :key="name">{{ name }}</li>
  </ul>
</template>
