<template>
    <section>
        <div class="container">
            <article>
                <h3>Visita Nuestra Sucursal</h3>
                <p>Horario: 11:00-20:00 hrs</p>
            </article>
            <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2707.071898259548!2d-71.24813355835826!3d-32.87795587684349!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x9689cd9b08345699%3A0x41b731e5d3805f02!2sLa18underink%20Tattoo!5e0!3m2!1ses!2scl!4v1689014641779!5m2!1ses!2scl"
                style="border:0;" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        </div>
    </section>
</template>

<style scoped>
section {
    width: 100%;
    height: 500px;
    padding: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.container {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 16px;
}

article {
    display: grid;
    place-items: center;
}

h3 {
    margin: 0;
    font-weight: bold;
    font-family: monospace;
    font-size: 24px;
}

p {
    margin: 0;
    font-size: 16px;
}

iframe {
    width: 280px;
    height: 280px;
}

@media (min-width: 768px) {

    /* Tamaño de pantalla de escritorio */
    .container {
        flex-direction: row;
    }

    article {
        margin-right: 16px;
        /* Espacio entre article y iframe */
    }
}</style>
