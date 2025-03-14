<script>
export default {
    name: 'soyResidente'
}
</script>
<template>
    <div class="residente_container">

        <div class="residente_background">
            <h2>Residentes</h2>

            <div class="residente_item1">
                <img src="../../public/img/justest.jpeg" alt="" srcset="">  

                <div class="residente_item2">
                <h3>Espacio para Residentes: Tu Movilidad es Nuestra Prioridad</h3>
                </div>
            </div>
            </div>

        <div class="residente_items">
                <div class="explicaciones">
                    <h4>¿Porque necesitamos Vehiculos?</h4>

                    <p>Para muchos de nosotros, los carros y las motos son la única forma de llegar al trabajo a tiempo, especialmente si vivimos en áreas más alejadas.</p>
                    <p>Necesitamos llevar a nuestros hijos a la escuela, hacer compras grandes o visitar a familiares que viven lejos. El transporte público no siempre es una opción viable.</p>
                </div>
                <p>Para nosotros es fundamental seguir estas medidas de seguridad:</p>
                <ul>
                    <li>Reduce la velocidad en zonas con peatones.</li>
                    <li>Utiliza el claxon solo en caso de emergencia.</li>
                    <li>Estaciona en lugares permitidos.</li>
                </ul>
            </div>
    </div>
</template>

<style scoped>
.residente_container {
    display: flex;
    flex-wrap: wrap;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    margin-top: 20px;
    text-align: center;
    
}

.residente_container h2 {
    margin-bottom: 22px;
}

.residente_item1 {
    margin-bottom: 20px;
}

.residente_item1 img {
    margin-bottom: 12px;
    border-radius: 10px;
}

.residente_background {
    background-color: rgb(17, 133, 23);
    width: 100%;
    padding: 10px;
    color: #fff;
    margin-bottom: 10px;
}

.residente_items {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    text-align: center;
    padding: 10px;
}

</style>

<!-- <script>
export default {
    name: 'soyResidente'
}
</script>
<template>
    <div class="residente_container">

        <h2>Residente</h2>

        <div class="residente_background">
            <img class="size-stroke size-right" src="../../public/img/paint_stroke_1.png" alt="" srcset="">
            <img class="size-stroke size-left" src="../../public/img/paint_stroke_2.png" alt="" srcset="">

            <div class="residente_item1">
                <img src="../../public/img/justest.jpeg" alt="" srcset="">  

                <div class="residente_item2">
                <h3>Espacio para Residentes: Tu Movilidad es Nuestra Prioridad</h3>
                </div>
            </div>
            </div>

        <div class="residente_items">
                <div class="explicaciones">
                    <h4>¿Porque necesitamos Vehiculos?</h4>

                    <p>Para muchos de nosotros, los carros y las motos son la única forma de llegar al trabajo a tiempo, especialmente si vivimos en áreas más alejadas.</p>
                    <p>Necesitamos llevar a nuestros hijos a la escuela, hacer compras grandes o visitar a familiares que viven lejos. El transporte público no siempre es una opción viable.</p>
                </div>
                <p>Para nosotros es fundamental seguir estas medidas de seguridad:</p>
                <ul>
                    <li>Reduce la velocidad en zonas con peatones.</li>
                    <li>Utiliza el claxon solo en caso de emergencia.</li>
                    <li>Estaciona en lugares permitidos.</li>
                </ul>
            </div>
    </div>
</template>

<style scoped>
.residente_container {
    display: flex;
    flex-wrap: wrap;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    margin-top: 20px;
    text-align: center;
    
}

.residente_container h2 {
    color: black;
    margin-bottom: 22px;
}

.residente_item1 {
    margin-bottom: 20px;
}

.residente_item1 img {
    margin-bottom: 12px;
    border-radius: 10px;
}

.residente_background {
    /* background-color: rgb(17, 133, 23); */
    width: 100%;
    padding: 10px;
    color: #fff;
    margin-bottom: 10px;
}

.residente_item2 {
    color: black;
}

.residente_items {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    text-align: center;
    padding: 10px;
}


.size-stroke {
    width: 250px;
    height: 150px;
    position: absolute;
    z-index: -1;
}

.size-right {
    position: absolute;
    bottom: -40em;
    left: 120px;
    rotate: 160deg;
}
.size-left {
    position: absolute;
    bottom: -31em;
    right: 8em;
}

</style> -->