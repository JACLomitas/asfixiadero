<script>
export default {
    name: 'soyDeportista'
}
</script>

<template>
    <div class="deportista_container">
  
      <div class="deportista_background">
        <h2>Deportista/Visitante</h2>
  
        <div class="deportista_item1">
          <img src="../../public/img/deportista_demo.jpg
          " alt="Deportista caminando" srcset="">
  
          <div class="deportista_item2">
            <h3>Espacio para Deportistas/Visitantes: Disfruta y Cuida Nuestro Entorno</h3>
          </div>
        </div>
      </div>
  
      <div class="deportista_items">
        <div class="explicaciones">
          <h4>¿Por qué amamos este lugar?</h4>
  
          <p>Este lugar es perfecto para caminar, correr y disfrutar de la naturaleza. Nos ayuda a mantenernos saludables y conectados con el entorno.</p>
          <p>Queremos seguir disfrutando de este espacio de forma segura y respetuosa con todos.</p>
        </div>
        <p>Para que todos podamos disfrutar, te pedimos que consideres lo siguiente:</p>
        <ul>
          <li>Mantente atento al tráfico y utiliza las aceras o senderos designados.</li>
          <li>Utiliza audífonos a un volumen moderado para estar atento a tu entorno.</li>
          <li>Respeta las señales de tránsito y las normas de convivencia.</li>
          <li>Recoge tu basura y ayuda a mantener limpio el entorno.</li>
          <li>Se amable y respetuoso con los residentes que utilizan vehículos. Recuerda que este es su hogar y su medio de transporte.</li>
          <li>Si ves algo sospechoso o peligroso, repórtalo a las autoridades locales.</li>
        </ul>
  
        <div class="respeto_mutuo">
            <h4>Respeto Mutuo: La Clave para una Convivencia Armoniosa</h4>
            <p>Entendemos que los residentes necesitan sus vehículos y nosotros queremos disfrutar de este espacio para hacer ejercicio. El respeto mutuo y la comprensión son fundamentales para una convivencia pacífica.</p>
        </div>
      </div>
    </div>
  </template>
  
  <style scoped>
  /* Puedes agregar estilos específicos para esta sección */
  .deportista_container {
    display: flex;
    flex-wrap: wrap;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    margin-top: 20px;
    text-align: center;
  }
  
  .deportista_background {
    background-color: rgb(255, 153, 0);
    width: 100%;
    padding: 10px;
    color: #fff;
    margin-bottom: 10px;
  }
  
  .deportista_item1 {
    margin-bottom: 12px;
    border-radius: 10px;
  }
  
  .deportista_items {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    text-align: center;
    padding: 10px;
  }

  .deportista_items ul li {
    margin: 5px;
  }
  
  /* .respeto_mutuo {

  } */

  .deportista_item1 img {
    width: 300px;
    height: 200px;
    border-radius: 10px;
  }
  </style>