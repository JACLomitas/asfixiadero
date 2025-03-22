<script>
export default {
    name: 'QuienesSomos'
}
</script>

<template>
    <div class="somos_info_container">
        <div class="somos">
            <h1>¿Quienes Somos?</h1>
        </div>
        <div class="somos_img">
            <img src="../../public/img/svg/howWeAre.svg" alt="" srcset="">
        </div>
        <div class="somos_info">
            <p>Somos la Junta de acción comunal, y queremos que, tanto residentes como deportistas nos unamos
                juntos como familia y emprendamos un viaje en busca de un asfixiadero mas seguro y armonioso</p>
        </div>
    </div>
</template>

<style scoped>
/* Estilos Generales - Mobile First */
.somos_info_container {
    display: flex;
    flex-wrap: wrap;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    text-align: center;
    font-family: 'Arial', sans-serif;
    color: #333;
    margin: 0 auto;
    max-width: 100%;     
    padding: 1rem;      
    box-sizing: border-box;
}

/* Section header */
.somos {
    font-size: 2rem;     /* Reduje el tamaño de fuente para móvil */
    margin-top: 1.5rem;  /* Reduje el margen superior para móvil */
}

/* Section information */
.somos_info {
    font-size: 1.2rem;   /* Reduje el tamaño de fuente para móvil */
    padding: 1rem;       /* Reduje el padding para móvil */
}

/* Section Image */
.somos_img {
    margin: 1rem;       /* Reduje el margen para móvil */
}

.somos_img img {
    width: 150px;        /* Reduje el tamaño para móvil */
    height: 150px;        /* Reduje el tamaño para móvil */
}

/* Media Queries para Responsividad */
/* Estilos para Tablets (landscape) */
@media (min-width: 768px) and (orientation: landscape) {
    .somos_info_container {
        font-size: 1.6rem;
    }

    .somos_img img {
        width: 400px;
        height: 400px;
    }
}

/* Estilos para Desktop */
@media (min-width: 1024px) {
    .somos_info_container {
        font-size: 1.8rem;
        width: 80%;
    }

    .somos_img img {
        width: 350px;
        height: 350px;
    }
}
</style>