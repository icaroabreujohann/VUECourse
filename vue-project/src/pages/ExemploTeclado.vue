<script setup>
    function keyMsg() {
        alert('Teste VueJs')
    }
</script>

<template>
    <input type="text" @keydown="keyMsg">
</template>