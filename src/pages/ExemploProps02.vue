<script setup>

    const props = defineProps(['nome', 'idade', 'cidade', 'cidades'])

    let capital = 'São Paulo '
    let cidades = ['São Paulo', 'Curitisa', 'Floripas']
</script>

<template>
    <h1>Nome: {{ nome }}</h1>
    <h1>Idade: {{ idade }}</h1>
    <h1>Cidade: {{ capital }}</h1>

    <ul>
        <li v-for="cidade in cidades">{{ cidade }}</li>
    </ul>


</template>