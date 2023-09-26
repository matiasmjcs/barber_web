<template>
    <section>
        <h2>Acerca de mí</h2>
        <article>
            <div class="perfil"></div>
            <p>Soy Ignacio, un barbero profesional con más de 8 años de experiencia. Mi objetivo es brindar servicios de alta calidad y resultados excepcionales a través de una atención personalizada y técnicas actualizadas. ¡Confía en mí para superar tus expectativas en cada visita a mi barbería!</p>
        </article>
    </section>
</template>

<style scoped>
section {
    width: 100%;
    background-color: #f5f5f5;
    padding: 40px;
    border-radius: 8px;
    text-align: center;
    margin: 20px 0px;
}

article {
    width: 100%;
    height: 100%;
    display: grid;
    grid-template-columns: 1fr 1fr;
    justify-items: center;
    align-items: center;
}


.perfil {
    width: 100%;
    height: 100%;
    min-height: 250px;
    background-image: url('../../assets/perfil.png');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}

h2 {
     font-size: 24px;
    text-align: center;
    font-family: monospace;
    margin-bottom: 16px;
}

p {
    min-width: 200px;
    font-size: 16px;
    color: #666666;
    text-align: start;
    margin: 10px;
    font-family: monospace;
}

@media (max-width: 650px) {
  article {
    grid-template-columns: 1fr;
    grid-template-rows: 1fr 1fr;
}

.perfil {
    background-size: 100%;
}

}


</style>
