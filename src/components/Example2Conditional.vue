<!-- SCRIPT -->
<script setup>
// Variables
let show = false;
let average = 4;
</script>

<!-- HTML -->
<template>
  <h1 v-if="show">Hello, Vue 3!</h1>

  <p v-if="average >= 7" style="color: green">Aprovado(a)</p>
  <p v-else-if="average >= 5 && average < 7" style="color: orange">Em exame</p>
  <p v-else style="color: red">Reprovado(a)</p>
</template>
