<!-- Script -->
<script setup>
// Variables
let nome = "Jeffy Mesquita";
let idade = 37;
let numero1 = 10;
let numero2 = 20;
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
