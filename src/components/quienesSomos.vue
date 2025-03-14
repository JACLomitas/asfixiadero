<script>
export default {
    name: 'quienesSomos'
}
</script>
<template>


    <div class="somos_info_container">

        <div class="somos">
        <h1>¿Quienes Somos?</h1>
    </div>
        <div class="somos_info">
        <p>Somos la Junta de acción comunal, y queremos que, tanto residentes como deportistas nos unamos 
            juntos como familia y emprendamos un viaje en busca de un asfixiadero mas seguro y armonioso</p>
    </div>
    <div class="somos_img"> <img src="../../public/img/svg/howWeAre.svg" alt="" srcset=""> </div>
    </div>

    
</template>

<style scoped>

.somos_info_container {
    display: flex;
    flex-wrap: wrap;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    /* margin-top: 50px; */
    text-align: center;
}

.somos {
    margin-top: 20px;
}


.somos_info {
    padding: 10px;
}

.somos_img {
    margin: 10px;
}

.somos_img img {
    width: 200px;
    height: 200px;
}

</style>