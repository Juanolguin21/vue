<template>
    <div class="cv-experience">
      <h2>Historial Laboral</h2>
      <div class="experience-item">
        <h3>Desarrollador Freelance</h3>
        <p>Diciembre 2016 - Enero 2025</p>
        <p>Mi Propio Jefe</p>
        <p>Aprendiedno LO nuuveo DIA A DIA</p>
      </div>
      <div class="experience-item">
        <h3>Tesoreria Banco Nación</h3>
        <p>Diciembre 2014 - Enero 2025</p>
        <p>Jefe interino del sector</p>
        <p>Postulado para el área de Sistemas</p>
      </div>
      <div class="experience-item">
        <h3>Tecnico Informatico CH-Computacion</h3>
        <p>marzo 2009- febrero 2014</p>
        <p>Tecnico a Cargo REMOTO Y PRESENCIAL</p>
        <p>Sistems-Redes-Hardware/Software-Soporte</p>
      </div>
      <!-- Agrega más elementos de experiencia aquí -->
    </div>
  </template>
  
  <script>
  export default {
    name: 'CvExperience'
  }
  </script>
  
  <style scoped>
   h2 {
      color: aliceblue;
  }
  h3 {
    color: brown;
    }
  .cv-experience {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 50%;
    margin-bottom: 20px;
  }
  
  .experience-item {
    margin-bottom: 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  </style>