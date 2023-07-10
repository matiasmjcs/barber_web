<template>
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-contact">
                    <h3>Contacto</h3>
                    <ul>
                        <li>Teléfono: + 569 4808 4826</li>
                        <li>instagram: _nachobarberink_</li>
                        <li>Dirección: esquina san martin con, 18 de Septiembre 110, Quillota, Valparaíso</li>
                    </ul>
                </div>
            </div>
            <div class="footer-bottom">
                <p>Derechos de autor &copy; 2023 - Todos los derechos reservados</p>
            </div>
        </div>
    </footer>
</template>

<style scoped>
/* Estilos para el footer */
.footer {
    background-color: black;
    color: white;
    padding: 40px 0;
    text-align: center;
}

.container {
    max-width: 960px;
    margin: 0 auto;
}

.footer-content {
    display: flex;
    justify-content: center;
}

.footer-contact {
    flex-basis: 100%;
}

.footer-contact h3 {
    color: white;
    margin-bottom: 20px;
}

.footer-contact ul {
    list-style: none;
    padding: 0;
}

.footer-contact ul li {
    margin-bottom: 10px;
}

.footer-bottom {
    margin-top: 20px;
}

.footer-bottom p {
    font-size: 14px;
    color: #999;
    margin: 0;
}
</style>
