<script>
export default {
    name: 'navbar',
    props: {
        scrollToSection: {
            type: Function,
            required: true // Indica que este prop es obligatorio
        }
    }
}
</script>

<template id="inicio">
<nav class="navbar navbar-expand-lg bg-light fixed-top">
    <div class="container-fluid">
        <a class="navbar-brand" href="#inicio"> <img src="../../public/img/JAC.png" alt="" srcset=""> Asfixiadero de Todos</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <div class="navbar-nav">
                <a class="nav-link active" aria-current="page" href="#inicio" @click.prevent="scrollToSection('inicio')">Inicio</a>
                <a class="nav-link" href="#somos" @click.prevent="scrollToSection('somos')">Somos</a>
                <a class="nav-link" href="#residentes" @click.prevent="scrollToSection('residentes')">Residentes</a>
                <a class="nav-link" href="#deportistas" @click.prevent="scrollToSection('deportistas')">Deportistas</a>
                <a class="nav-link" href="#solucion" @click.prevent="scrollToSection('solucion')">Solución</a>
            </div>
        </div>
    </div>
</nav>
</template>

<style scoped>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-size: 100.10%;
    font-family: "Ysabeau SC", sans-serif;
    font-optical-sizing: auto;
    font-weight: weight;
}

.navbar {
    padding: 15px;
    transition: background-color 0.3s ease-in-out; /* Transición suave */
}

.navbar.fixed-top {
    background-color: rgba(255, 255, 255, 0.9); /* Fondo semitransparente */
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Sombra para darle un efecto flotante */
}

.navbar-brand {
    margin-right: 10px;
}

.navbar img {
    width: 40px;
    height: 40px;
    margin-right: 5px;
}
</style>