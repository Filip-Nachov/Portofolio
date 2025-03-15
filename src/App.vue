<script setup>
import { ref, reactive } from 'vue'

const about = reactive({
    name: 'Filip Nachov',
    tags: [
    ' Macedonian',
    ' Freelance', ' UTC+1',
    ' English', ' Available'
    ],
    github: 'https://github.com/Filip-Nachov',
    contact: 'fnachov@gmail.com'
})

</script>

<template>
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

#about {
    background-color: #0c0d0c;
    color: white;
    border-color: purple;
}

</style>
