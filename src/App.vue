<script setup>
import navbar from './components/navbar.vue'
import info from './components/info.vue'
import quienesSomos from './components/quienesSomos.vue'
import soyResidente from './components/soyResidente.vue'
import soyDeportista from './components/soyDeportista.vue'
import footerApp from './components/footer.vue'
</script>

<template>
<navbar />
<div class="principal_info">
  <img src="../public/img/asfixiadero__nav.jpg" alt="" srcset="">
  <div class="text_info">
    <p>Convivencia en Movimiento Un Espacio para Todos</p>
  </div>
</div>
<info />
<quienesSomos />
<soyResidente />
<soyDeportista />
<footerApp />
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.principal_info {
  position: relative;
  width: 100%; 
}

.principal_info img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  filter: brightness(0.2); /* Oscurece la imagen */
}

.principal_info .text_info {
  position: absolute;
  top: 50%; /* Centra verticalmente */
  left: 50%; /* Centra horizontalmente */
  transform: translate(-50%, -50%); /* Ajusta el centrado */
  color: rgb(238, 238, 238); /* Color del texto */
  padding: 20px;
  text-align: center;
  line-height: 16px;
  width: 80%; /* Define un ancho para el texto (ajusta según sea necesario) */
  font-family: "Ysabeau SC", sans-serif;
font-optical-sizing: auto;
font-weight: weight;
}
</style>
