<script setup>
import navbar from './components/navbar.vue'
import info from './components/info.vue'
import quienesSomos from './components/quienesSomos.vue'
import soyResidente from './components/soyResidente.vue'
import soyDeportista from './components/soyDeportista.vue'
import solucion from './components/solucion.vue'
import footerApp from './components/footer.vue'
</script>

<template>
    <navbar />
    <div class="principal-info">
        <div class="image-container">
            <img src="../public/img/asifixiadero_slider.jpg" alt="img_prinsipal" class="principal-image">
            <div class="text-info">
                <p>Convivencia en Movimiento Un Espacio para Todos</p>
            </div>
        </div>
    </div>
    <info />
    <quienesSomos />
    <soyResidente />
    <soyDeportista />
    <solucion />
    <footerApp />
</template>

<style scoped>
/* Estilos Generales - Mobile First */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Principal Info Section */
.principal-info {
    position: relative;
    width: 100%;
}

.image-container {
    position: relative;
}

.principal-info .principal-image {
    width: 100%;
    height: 200px; /* Altura inicial para móvil */
    object-fit: cover;
    filter: brightness(0.2);
    transition: filter 0.3s ease-in-out;
}

.principal-info .principal-image:hover {
    filter: brightness(0.5);
}

.principal-info .text-info {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: rgb(255, 255, 255);
    padding: 10px; /* Reduje el padding para móvil */
    text-align: center;
    line-height: 1.2;   /* Ajusta el espaciado entre líneas */
    width: 80%;
    font-family: "Ysabeau SC", sans-serif;
    font-optical-sizing: auto;
    font-weight: weight;
    font-size: 1.2rem; /* Ajuste el tamaño de fuente inicial */
}

.text-info p {
  color: rgb(255, 255, 255);
}

/* Media Queries para Responsividad */
/* Estilos para Tablets (landscape) */
@media (min-width: 768px) and (orientation: landscape) {
    .principal-info .principal-image {
        height: 300px;
    }

    .principal-info .text-info {
        font-size: 1.5rem;
        line-height: 1.4;
        padding: 15px; /* Aumenta el padding en tablet */
    }
}

/* Estilos para Desktop */
@media (min-width: 1024px) {
    .principal-info .principal-image {
        height: 400px;
    }

    .principal-info .text-info {
        font-size: 1.8rem;
        line-height: 1.6;
        padding: 20px; /* Aumenta el padding en desktop */
    }
}
</style>