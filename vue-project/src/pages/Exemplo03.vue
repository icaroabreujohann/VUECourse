<script setup>
    const names = ['John', 'Bruno', 'João', 'Icaro']
</script>

<template>

    <ul>
        <li v-for="name in names">{{ name }}</li>
    </ul>

</template>