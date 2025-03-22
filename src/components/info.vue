<script>
import Typed from 'typed.js';

export default {
    name: 'info',
    mounted() {
        if (window.innerWidth >= 1024) { // Solo aplica Typed.js en pantallas de escritorio
            var typed = new Typed('.typed_info', {
                strings: [" Buscamos tu mayor seguridad y bienestar.",
                          "Promovemos el respeto mutuo y la convivencia pacífica entre residentes y visitantes en el Asfixiadero."],
                typeSpeed: 30
            });
        } else {
            document.querySelector('.typed_info').textContent = "Buscamos tu mayor seguridad y bienestar. Promovemos el respeto mutuo y la convivencia pacífica entre residentes y visitantes en el Asfixiadero.";
        }
    }
}
</script>

<template>
    <div class="info-container">
        <p class="typed_info"></p>
    </div>
</template>

<style scoped>
/* Estilos Generales - Mobile First */
.info-container {
    display: flex;
    justify-content: flex-start; /* Alinea el contenido a la izquierda */
    text-align: left; /* Alinea el texto a la izquierda */
    background-color: orange;
    padding: 1rem; /* Ajusta el padding para móvil */
    font-optical-sizing: auto;
    font-weight: normal;
    font-style: normal;
    font-size: 1rem;  /* Ajusta el tamaño de la fuente para móvil */
    line-height: 1.5; /* Espaciado entre líneas para mejorar la legibilidad */
}

.typed_info {
    display: flex;
    text-align: center;
}

/* Media Queries para Responsividad */
/* Estilos para Tablets (landscape) */
@media (min-width: 768px) and (orientation: landscape) {
    .info-container {
        padding: 1.5rem;
        font-size: 1.2rem;
    }
}

/* Estilos para Desktop */
@media (min-width: 1024px) {
    .info-container {
        padding: 2rem;
        font-size: 1.4rem;
    }
}
</style>