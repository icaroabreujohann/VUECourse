<script setup>
    const exibir = false
    const media = 3
</script>

<template>
    <h1 v-if="exibir">Hello World!</h1>

    <p v-if="media>=8">Aprovado</p>
    <p v-else-if="media >=6">Exame</p>
    <p v-else>Reprovado</p>
</template>