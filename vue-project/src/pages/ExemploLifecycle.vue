<script setup>
    import { onMounted, ref } from 'vue'

    let text = ref('Hello World!')

    onMounted( () => {
        setTimeout(() => {
            text.value = 'Alterando Texto'
        }, 3000)
    } );
</script>

<template>
    <h1>{{ text }}</h1>
</template>