<script setup>
    const text = '<p style="color:red">V-HTML</p>'
</script>

<template>
    <p v-html="text"></p>
    <p>{{ text }}</p>
</template>