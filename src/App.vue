<script setup>
import { ref } from 'vue'

const count = ref(0)

console.log(count)

function increment() {
  count.value++
}

function decrement() {
    count.value--
}
</script>

<template>
  <button style="height: 200px; width: 300px; font-size: 100px">
    {{ count }}
  </button>
  <br>
  <button style="height: 200px; width: 400px; font-size: 100px" @click="increment">
    increase
  </button>
  <br>
  <button style="height: 200px; width: 400px; font-size: 100px" @click="decrement">
    decrease
  </button>
</template>

<style>
body{
    background-color: #0d0c0d;
    color: white;
    font-family: "Roboto", sans-serif;
    font-weight: 400;
    font-style: normal;
}

button {
    background-color: #0c0d0c;
    color: white;
    border-radius: 20px;
    border-color: #0d0c0d;
}

</style>
