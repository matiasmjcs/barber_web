<script setup lang="ts">
</script>

<template>
    <header class="header">
        <article class="article-title">
            <h2>Bienvenidos a</h2>
            <h3>mi Barberia Profesional</h3>
        </article>
    </header>
</template>

<style scoped>
.header {
    width: 100%;
    height: 500px;
    overflow: hidden;
    display: grid;
    place-content: center;
    background-image: url('../../assets/img-header.png');
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
}

.article-title {
    place-self: center;
}

h2 {
    justify-self: center;
    align-self: end;
    color: white;
    font-size: 24px;
    text-align: center;
    font-weight: bold;
    font-family: monospace;
}

h3 {
    justify-self: center;
    align-self: start;
    color: white;
    font-size: 32px;
    text-align: center;
    font-weight: bold;
    font-family: monospace;
}

</style>
