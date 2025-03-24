<script>
export default {
    name: 'SoyDeportista'
}
</script>

<template>
    <div class="deportista-container">

        <section class="hero">
            <div class="hero-image-container">
                <img src="../../public/img/deportista_01.jpg" alt="Deportista caminando" class="hero-image">
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

                <h2 class="h2-mg">Cuidemos juntos este espacio:</h2>
                <ul class="guidelines">
                    <li>Mantente atento al tráfico</li>
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
    height: 250px;   
    object-fit: cover;
    filter: brightness(50%);
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
    font-size: 2rem;     
    font-weight: bold;
    margin-bottom: 0.5rem;
}

.hero-content p {
    font-size: 1rem;
}

/* Info Section */
.info-section {
    display: flex;
    flex-direction: column;
    text-align: left;
    align-items: flex-start;
    padding: 1.5rem;
    max-width: 100%;
    margin: 0 auto;
}

.text-container {
    width: 100%;
    text-align: left;
}

.text-container h2 {
    font-size: 1.7rem;
    color: #212529;
    margin-bottom: 0.7rem;
}

.text-container p {
    font-size: 1rem;      
    line-height: 1.5;
    color: #495057;
    margin-bottom: 1rem;
}

.guidelines {
    list-style: none;
    padding: 0;
    margin-bottom: 1rem;
}

.guidelines li {
    padding: 0.4rem 0;
    border-bottom: 1px solid #dee2e6;
    position: relative;
    padding-left: 1.8rem;  
    font-size: 1rem;
}

.guidelines li::before {
    content: '✓';
    position: absolute;
    left: 0;
    top: 50%;
    transform: translateY(-50%);
    color: #28a745;
    font-weight: bold;
    font-size: 1.2rem;
}

.respeto-mutuo {
    padding: 1rem;
    background-color: #f1f5f9;
    border-radius: 8px;
}

.respeto-mutuo h2 {
    font-size: 1.2rem;
    margin-bottom: 0.7rem;
}

.respeto-mutuo p {
    font-size: 1rem;
}

.respeto-mutuo p {
    font-size: 1rem;
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

    .guidelines {
        text-align: left;
    }

    .text-container ul {
            display:flex;
            flex-direction: row;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            margin: 50px;
        }
    
.text-container ul li {
        font-size: 1.8rem;
    }
}
</style>
