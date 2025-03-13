<script setup>
import { ref } from 'vue'

const count = ref(0)

console.log(count)

function increment() {
  count.value++
}
</script>

<template>
  <button @click="increment">
    {{ count }}
  </button>
</template>

<style>
body{
    background-color: #0d0c0d;
    color: white;
    font-weight: bold;
}

button {
    background-color: #0c0d0c;
    color: white;
    border-radius: 20px;
    border-color: #0d0c0d;
}

</style>
