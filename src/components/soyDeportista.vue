<script>
export default {
    name: 'SoyDeportista'
}
</script>

<template>
    <div class="deportista-container">

        <section class="hero">
            <div class="hero-image-container">
                <img src="../../public/img/deportista_demo.jpg" alt="Deportista caminando" class="hero-image">
                <div class="hero-content">
                    <h1>Deportistas y Visitantes</h1>
                    <p>¡Bienvenido! Disfruta y cuida este espacio natural que tanto amamos.</p>
                </div>
            </div>
        </section>

        <section class="info-section">
            <div class="text-container">
                <h2>¿Por qué amamos este lugar?</h2>
                <p>Este entorno es ideal para conectar con la naturaleza, mantenernos activos y recargar energías. ¡Es un tesoro que debemos proteger!</p>

                <h2>Cuidemos juntos este espacio:</h2>
                <ul class="guidelines">
                    <li>Mantente atento al tráfico y utiliza las aceras o senderos designados.</li>
                    <li>Modera el volumen de tus audífonos para estar alerta a tu entorno.</li>
                    <li>Respeta las señales de tránsito y las normas de convivencia.</li>
                    <li>Deposita la basura en los contenedores adecuados.</li>
                    <li>Sé cortés y considerado con los residentes y sus vehículos.</li>
                    <li>Reporta cualquier situación sospechosa a las autoridades.</li>
                </ul>

                <div class="respeto-mutuo">
                    <h2>Respeto Mutuo: Nuestra Clave para Convivir Armónicamente</h2>
                    <p>Entendemos las necesidades de movilidad de los residentes y valoramos tu compromiso con el bienestar de nuestra comunidad. Juntos, podemos crear un espacio donde todos disfrutemos.</p>
                </div>
            </div>
        </section>

    </div>
</template>

<style scoped>
/* Estilos Generales - Mobile First */
.deportista-container {
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
    filter: brightness(70%);
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
    text-align: left;
    align-items: flex-start;
    padding: 1.5rem;      /* Reduje el padding para móvil */
    max-width: 100%;     /* Ocupar todo el ancho en móvil */
    margin: 0 auto;
}

.text-container {
    width: 100%;
    text-align: left;
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
    color: #28a745;
    font-weight: bold;
    font-size: 1.2rem;  /* Reduje el tamaño de fuente para móvil */
}

.respeto-mutuo {
    padding: 1rem;       /* Reduje el padding para móvil */
    background-color: #f1f5f9;
    border-radius: 8px;
}

.respeto-mutuo h2 {
    font-size: 1.7rem;    /* Reduje el tamaño de fuente para móvil */
    margin-bottom: 0.7rem; /* Reduje el margen inferior para móvil */
}

.respeto-mutuo p {
    font-size: 1rem;      /* Reduje el tamaño de fuente para móvil */
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
        align-items: flex-start;
        text-align: left;
    }

    .text-container {
        width: 50%;
    }

    /* Asegurar que las guidelines estén alineadas a la izquierda en tablet */
    .guidelines {
        text-align: left;
    }
     .hero-image {
        height: 300px;
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
        align-items: flex-start;
        text-align: left;
    }

    .text-container {
        width: 50%;
    }
    .hero-image {
        height: 400px;
    }

    /* Asegurar que las guidelines estén alineadas a la izquierda en desktop */
    .guidelines {
        text-align: left;
    }
}
</style>
