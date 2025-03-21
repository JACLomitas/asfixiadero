<script>
export default {
    name: 'navbar'
}
</script>
<template>
<nav class="navbar navbar-expand-lg bg-light">
    <div class="container-fluid">
    <a class="navbar-brand" href="#"> <img src="../../public/img/JAC.png" alt="" srcset=""> Asfixiadero de Todos</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
        <a class="nav-link active" aria-current="page" href="#">Inicio</a>
        <a class="nav-link" href="#">Somos</a>
        <a class="nav-link" href="#">Residentes</a>
        <a class="nav-link" href="#">Deportistas</a>
        <a class="nav-link" href="#">Solucion</a>
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
}

.navbar img {
    width: 40px;
    height: 40px;
    margin-right: 5px;
}
</style>