<script>
export default {
    name: 'solucion'
}
</script>

<template>
    <div class="solucion-container">
        <section class="hero">
            <div class="hero-content">
                <h1>Construyendo Juntos una Mejor Convivencia en El Asfixiadero</h1>
                <p>Uniendo voces, respetando caminos, creando armonía entre residentes y deportistas.</p>
            </div>
        </section>

        <section class="resumen">
            <h2>Entendiendo los Dos Lados:</h2>
            <div class="resumen-contenido">
                <div class="residente">
                    <h3>Residentes:</h3>
                    <p>Necesitamos nuestros vehículos para el trabajo, la escuela y la familia. ¡Nuestra movilidad es esencial!</p>
                </div>
                <div class="deportista">
                    <h3>Deportistas y Visitantes:</h3>
                    <p>Amamos este espacio para ejercitarnos y conectar con la naturaleza. ¡Queremos un entorno seguro y agradable!</p>
                </div>
            </div>
        </section>

        <section class="soluciones">
            <h2>Propuestas para un Futuro en Armonía:</h2>
            <ul class="lista-soluciones">
                <li><strong>Más Espacios Seguros:</strong> Ampliar aceras y crear ciclovías protegidas para peatones y deportistas.</li>
                <li><strong>Horarios Inteligentes:</strong> Explorar horarios diferenciados para actividades deportivas y tráfico vehicular pesado.</li>
                <li><strong>Conciencia y Respeto:</strong> Lanzar campañas educativas para fomentar la empatía y el conocimiento de las normas.</li>
                <li><strong>Rutas Alternativas:</strong> Señalizar claramente rutas alternativas para vehículos en horarios de mayor afluencia.</li>
                <li><strong>Diálogo Abierto:</strong> Facilitar reuniones periódicas entre residentes y deportistas para construir soluciones conjuntas.</li>
                <li><strong>Cumplimiento de Normas:</strong> Reforzar el cumplimiento de las normas de tránsito y convivencia para garantizar la seguridad.</li>
            </ul>
        </section>

        <section class="conclusion">
            <h2>Conclusión: Un Compromiso con el Respeto Mutuo</h2>
            <p>La clave para una convivencia exitosa en El Asfixiadero reside en el respeto mutuo, la comprensión y la voluntad de encontrar soluciones que beneficien a todos. ¡Juntos, podemos crear un espacio donde la movilidad y la actividad física coexistan en armonía, construyendo una mejor Sabaneta para todos!</p>
        </section>
    </div>
</template>

<style scoped>
/* Estilos Generales - Mobile First */
.solucion-container {
    font-family: 'Arial', sans-serif;
    color: #333;
    margin: 0 auto;
    padding: 1rem;
    box-sizing: border-box;
    text-align: center;
    max-width: 1200px;
}

/* Hero Section */
.hero {
    background-color: #1E8449; /* Verde Sabaneta */
    color: white;
    padding: 2rem 1rem;
    margin-bottom: 2rem;
}

.hero-content h1 {
    font-size: 2.2rem;
    font-weight: bold;
    margin-bottom: 0.5rem;
}

.hero-content p {
    font-size: 1.2rem;
}

/* Resumen Section */
.resumen {
    text-align: left;
    padding: 1rem;
    margin-bottom: 2rem;
}

.resumen h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
    color: #212529;
}

.resumen-contenido {
    display: flex;
    flex-direction: column;
}

.resumen-contenido div {
    margin-bottom: 1rem;
    padding: 1rem;
    border-radius: 8px;
}

.residente {
    background-color: #F9E79F; /* Amarillo Claro */
}

.deportista {
    background-color: #E8F8F5; /* Verde Muy Claro */
}

.resumen-contenido h3 {
    font-size: 1.5rem;
    color: #34495E;
    margin-bottom: 0.5rem;
}

.resumen-contenido p {
    font-size: 1.1rem;
    line-height: 1.6;
    color: #495057;
}

/* Soluciones Section */
.soluciones {
    text-align: left;
    padding: 1rem;
}

.soluciones h2 {
    font-size: 2rem;
    margin-bottom: 1.5rem;
    color: #212529;
}

.lista-soluciones {
    list-style: none;
    padding: 0;
}

.lista-soluciones li {
    padding: 0.7rem 0;
    border-bottom: 1px solid #dee2e6;
    font-size: 1.2rem;
    line-height: 1.6;
    color: #495057;
}

/* Conclusion Section */
.conclusion {
    text-align: left;
    padding: 1rem;
    margin-top: 2rem;
}

.conclusion h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
    color: #212529;
}

.conclusion p {
    font-size: 1.2rem;
    line-height: 1.7;
    color: #495057;
}

/* Media Queries para Responsividad */
/* Estilos para Tablets (landscape) */
@media (min-width: 768px) and (orientation: landscape) {
    .hero-content h1 {
        font-size: 3rem;
    }

    .hero-content p {
        font-size: 1.4rem;
    }

    .resumen h2 {
        font-size: 2.3rem;
    }

    .soluciones h2 {
        font-size: 2.3rem;
    }

    .conclusion h2 {
        font-size: 2.3rem;
    }

    .resumen-contenido {
        flex-direction: row;
        justify-content: space-between;
    }

    .resumen-contenido div {
        width: 48%;
    }
}

/* Estilos para Desktop */
@media (min-width: 1024px) {
    .hero-content h1 {
        font-size: 3.5rem;
    }

    .hero-content p {
        font-size: 1.6rem;
    }

    .resumen h2 {
        font-size: 2.5rem;
    }

    .soluciones h2 {
        font-size: 2.5rem;
    }

    .conclusion h2 {
        font-size: 2.5rem;
    }

    .resumen-contenido div {
        width: 45%;
        padding: 1.5rem;
    }

    .solucion-item p {
        font-size: 1.3rem;
    }
}
</style>