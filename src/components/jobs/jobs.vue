<script lang="ts" setup>
</script>
<template>
    <section>
        <h2>Servicios</h2>
        <section class="section-jobs">

            <article>
                <img src="../../assets/tijeras.png" alt="imagen de tijeras" />
            <h3>Corte de cabello</h3>
            <p class="parrafo">Asesoría, corte de cabello. Incluye peinado con cera para peinar</p>
        </article>

        <article>
            <img src="../../assets/barba.png" alt="imagen de tijeras" />
            <h3>Perfilado de barba</h3>
            <p class="parrafo">Asesoría, recorte y arreglo de barba</p>
        </article>
        
        <article>
            <img src="../../assets/navaja.png" alt="imagen de tijeras" />
            <h3>lineas y Diseños</h3>
            <p class="parrafo">lineas simples y Diseños complejos a elección del Cliente</p>
        </article>
        
    </section>
    </section>
</template>

<style scoped>
.section-jobs {
    margin: 20px 0px;
    width: 100%;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

h2 {
    font-size: 24px;
    text-align: center;
    font-family: monospace;
}

article {
    width: 250px;
    height: 250px;
    margin: 20px;
    display: grid;
    justify-content: center;
    justify-items: center;
    grid-template-rows: 1.5fr .5fr 1fr;
}

article img {
    width: 70px;
    height: 70px;
}

.parrafo {
    text-align: center;
    font-family: monospace;
    text-align: justify;
}
</style>