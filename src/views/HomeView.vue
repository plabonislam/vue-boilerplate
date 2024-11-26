<script setup lang="ts">
import TheWelcome from '../components/TheWelcome.vue'
let test:string = "hi" 
</script>

<template>
  <main>
    <p> {{test}} </p>
    <TheWelcome />
  </main>
</template>
