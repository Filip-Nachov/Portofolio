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


