<template>
    <div class="cv-education">
      <h2>Formación</h2>
      <div class="education-item">
        <h3>Data Science</h3>
        <p>Ene 2025 - Coderhouse</p>
        <p>Carrera En curso</p>
      </div>
      <div class="education-item">
        <h3>FullStack Developer</h3>
        <p>Feb 2023 - NUCBA</p>
        <p>Finalizado Junio 2024</p>
      </div>
      <div class="education-item">
        <h3>Licenciado en Informatica</h3>
        <p>Mar 2009 - Universidad Atlantida Argentina</p>
        <p>Finalizado mayo 2014</p>
      </div>
      <div class="education-item">
        <h3>Tecnico Informatico</h3>
        <p>Jun 2010 - Universidad Atlantida Argentina</p>
        <p>Finalizado Ago 2012</p>
      </div>
      <!-- Agrega más elementos de educación aquí -->
    </div>
  </template>
  
  <script>
  export default {
    name: 'CvEducation'
  }
  </script>
  
  <style scoped>
   h2 {
      color: aliceblue;
  }
    h3 {
    color: brown;
    }
  .cv-education {
    margin-bottom: 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 50%;
    
  }
  
  .education-item {
    margin-bottom: 10px;
    width: 80%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    
  }
  </style>