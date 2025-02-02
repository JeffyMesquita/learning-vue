<!-- Script -->
<script setup>
// Variables
let nome = "Jeffy";
let idade = 27;
let numero1 = 10;
let numero2 = 5;
</script>

<!-- HTML -->
<template>
  <p>
    {{ "Hello, " + nome + " você tem " + idade + " anos." }}
  </p>
  <p>
    {{ numero1 + numero2 }}
  </p>
</template>
