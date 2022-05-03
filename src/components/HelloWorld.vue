<script setup lang="ts">
import { ref } from 'vue'
import Haha1 from "./Haha1.vue";
import Haha2 from "./Haha2.vue";

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
    <h1>{{ msg }}</h1>

    <Haha1/>
    <Haha2/>
</template>

<style scoped>
a {
    color: #42b983;
}

label {
    margin: 0 0.5em;
    font-weight: bold;
}

code {
    background-color: #eee;
    padding: 2px 4px;
    border-radius: 4px;
    color: #304455;
}
</style>
