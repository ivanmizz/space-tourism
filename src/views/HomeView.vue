<script setup>
import TheWelcome from '../components/TheWelcome.vue'
import destinations from '/data.json'

</script>

<template>
  <main>
    <TheWelcome />
    <p >
      my name is my {{ destinations.name }}
      </p>
  </main>
</template>
