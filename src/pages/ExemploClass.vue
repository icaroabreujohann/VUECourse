<script setup>
    const validator = false
</script>

<style>
    .ifTrue {
    color: green;
    }

    .ifFalse {
    color: red;
    }
</style>

<template>
    <h1 :class="validator ? 'ifTrue' : 'ifFalse'"> Utilizando CSS Classes</h1>
</template>