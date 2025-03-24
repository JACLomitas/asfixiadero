<script>
export default {
    name: 'SoyResidente'
}
</script>

<template>
    <div class="residente-container">

        <section class="hero">
            <div class="hero-image-container">
                <img src="../../public/img/comunidad_02.jpg" alt="Vehículos en Sabaneta" class="hero-image">
                <div class="hero-content">
                    <h1>Residentes</h1>
                    <p>Tu movilidad es nuestra prioridad</p>
                </div>
            </div>
        </section>

        <section class="info-section">
            <div class="text-container">
                <h2>¿Por qué necesitamos Vehículos?</h2>
                <p>Para muchos de nosotros, los carros y las motos son la única forma de llegar al trabajo a tiempo, especialmente si vivimos en áreas más alejadas.</p>
                <p>Necesitamos llevar a nuestros hijos a la escuela, hacer compras grandes o visitar a familiares que viven lejos. El transporte público no siempre es una opción viable.</p>

                <h2 class="h2-mg">Para nosotros es fundamental seguir estas medidas de seguridad:</h2>
                <ul class="guidelines">
                    <li>Reducir la velocidad en zonas concurridas </li>
                    <li>Utiliza el claxon solo en caso de emergencia.</li>
                    <li>Estaciona en lugares permitidos.</li>
                </ul>

                <div class="compromiso">
                    <h2>Nuestro Compromiso: Movilidad Segura y Respetuosa</h2>
                </div>
            </div>
        </section>

    </div>
</template>

<style scoped>
/* Estilos Generales - Mobile First */
.residente-container {
    font-family: 'Arial', sans-serif;
    color: #333;
    margin: 0 auto;
    padding: 1rem; /* Reduje el padding general para móvil */
    box-sizing: border-box;
    text-align: center;
    max-width: 100%;   /* Ocupar todo el ancho en móvil */
}

/* Hero Section */
.hero {
    position: relative;
    text-align: center;
    overflow: hidden;
    margin-bottom: 0.1rem; /* Reduje el margen inferior para móvil */
    padding: 2rem 0rem; /* Reduje el padding para móvil */
}

.hero-image-container {
    position: relative;
    overflow: hidden;
}

.hero-image {
    width: 100%;
    height: 250px;       /* Reduje la altura para móvil */
    object-fit: cover;
    filter: brightness(60%);
}

.hero-image-container img {
    border-radius: 20px 10px 30px 10px;
}

.hero-content {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
    padding: 10px;
    width: 100%;
    box-sizing: border-box;
}

.hero-content h1 {
    font-size: 2rem;      /* Reduje el tamaño de fuente para móvil */
    font-weight: bold;
    margin-bottom: 0.5rem; /* Reduje el margen inferior para móvil */
}

.hero-content p {
    font-size: 1rem;      /* Reduje el tamaño de fuente para móvil */
}

/* Info Section */
.info-section {
    display: flex;
    flex-direction: column;
    padding: 1.5rem;      /* Reduje el padding para móvil */
    max-width: 100%;     /* Ocupar todo el ancho en móvil */
    margin: 0 auto;
    text-align: left;
}

.text-container {
    text-align: left;
    width: 100%;
}

.text-container h2 {
    font-size: 1.7rem;    /* Reduje el tamaño de fuente para móvil */
    color: #212529;
    margin-bottom: 0.7rem; /* Reduje el margen inferior para móvil */
}

.text-container p {
    font-size: 1rem;      /* Reduje el tamaño de fuente para móvil */
    line-height: 1.5;
    color: #495057;
    margin-bottom: 1rem;   /* Reduje el margen inferior para móvil */
}

.guidelines {
    list-style: none;
    padding: 0;
    margin-bottom: 1rem;   /* Reduje el margen inferior para móvil */
}

.guidelines li {
    padding: 0.4rem 0;    /* Reduje el padding vertical para móvil */
    border-bottom: 1px solid #dee2e6;
    position: relative;
    padding-left: 1.8rem;  /* Reduje el espacio para el "check" para móvil */
    font-size: 1rem;      /* Reduje el tamaño de fuente para móvil */
}

.guidelines li::before {
    content: '✓';
    position: absolute;
    left: 0;
    top: 50%;
    transform: translateY(-50%);
    color: #F39C12; /* Naranja Sabaneta */
    font-weight: bold;
    font-size: 1.2rem;  /* Reduje el tamaño de fuente para móvil */
}

.compromiso {
    padding: 1rem;       /* Reduje el padding para móvil */
    background-color: #F9E79F; /* Amarillo Claro */
    border-radius: 8px;
}

.compromiso h2 {
    font-size: 1rem;    /* Reduje el tamaño de fuente para móvil */
    margin-bottom: 0.7rem; /* Reduje el margen inferior para móvil */
}

.compromiso p {
    font-size: 0.5rem;      /* Reduje el tamaño de fuente para móvil */
}

/* Media Queries para Responsividad */
/* Estilos para Tablets (landscape) */
@media (min-width: 768px) and (orientation: landscape) {
    .hero-content h1 {
        font-size: 3.5rem;
    }

    .hero-content p {
        font-size: 1.4rem;
    }

    .info-section {
        flex-direction: row;
        justify-content: center;
        align-items: center;
        text-align: center;
    }

    .text-container {
        width: 100%;
        text-align: center;
        padding: 50px;
    }

    .text-container p {
        font-size: 1.4rem;
    }

    .text-container .h2-mg {
        margin-top: 50px;
    }

    /* Asegurar que las guidelines estén alineadas a la izquierda en tablet */
    .guidelines {
        text-align: left;
    }
    .hero-image {
        height: 300px;
    }

    .text-container ul {
        display:flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        margin: 50px;
    }

    .text-container ul li {
        font-size: 1.4rem;
    }
}

/* Estilos para Desktop */
@media (min-width: 1024px) {
    .hero-content h1 {
        font-size: 4rem;
    }

    .hero-content p {
        font-size: 1.6rem;
    }

    .info-section {
        flex-direction: row;
        justify-content: center;
        align-items: center;
        text-align: center;
    }
    

    .info-section h2 {
        font-size: 3.3rem;
    }

    .text-container {
        width: 100%;
        text-align: center;
        padding: 50px;
    }

    .text-container p {
        font-size: 1.4rem;
    }

    .text-container .h2-mg {
        margin-top: 50px;
    }

    .hero-image {
        height: 400px;
    }

    /* Asegurar que las guidelines estén alineadas a la izquierda en desktop */
    .guidelines {
        text-align: left;
    }

    .text-container ul {
        display:flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        margin: 50px;
    }

    .text-container ul li {
        font-size: 1.8rem;
    }
}
</style>
