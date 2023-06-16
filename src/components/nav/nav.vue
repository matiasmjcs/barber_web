<script setup lang="ts">
</script>

<template>
    <nav class="nav">
        <p>Inicio</p>
        <p>Trabajos</p>
    </nav>
</template>

<style scoped>
    .nav {
        display: flex;
        align-items: center;
        padding: 10px;
        gap: 5px;
    }
    .nav p {
        font-size: 20px;
        cursor: pointer;
        color:aliceblue;
        margin-left: 10px;
    }
    .nav p:hover {
        color: antiquewhite;
        transform: all .3s linear;
        transform: scale(1.1);
    }
</style>
