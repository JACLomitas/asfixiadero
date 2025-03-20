<script>
export default {
    name: 'info'
}
</script>

<template>
    <div class="info-container">
        <p>Promovemos el respeto mutuo y la convivencia pacífica entre residentes y visitantes en el Asfixiadero</p>
    </div>
</template>

<style scoped>
/* Estilos Generales - Mobile First */
.info-container {
    display: flex;
    text-align: center;
    background-color: orange;
    padding: 1rem; /* Ajusta el padding para móvil */
    font-optical-sizing: auto;
    font-weight: normal;
    font-style: normal;
    font-size: 1rem;  /* Ajusta el tamaño de la fuente para móvil */
    line-height: 1.5; /* Espaciado entre líneas para mejorar la legibilidad */
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