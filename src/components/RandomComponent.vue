<script setup lang="ts">
import { ref } from 'vue'

const count = ref(0)
setTimeout(() => {
    count.value = Math.random();
}, 1000)

</script>

<template>
    <h1>{{ count }}</h1> 222 1 6 64 1 1 1 111 111  13 131
</template>
