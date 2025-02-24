<script setup>
import { ref } from 'vue';

    let text = ref("")
</script>

<template>
    <input type="text" v-model="text">
    <p>{{ text }}</p>
</template>