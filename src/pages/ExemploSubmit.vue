<script setup>
    function validForm(event) {
        alert('Formulário Enviado')
        event.preventDefault();
        
    }
</script>

<template>
    <form action="http://youtube.com" @submit="validForm">

        <input type="submit" value="Enviar">

    </form>
</template>