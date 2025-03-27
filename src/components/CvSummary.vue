<template>
    <div class="cv-summary">
      <h2>Resumen Profesional</h2>
      <p>Soy un profesional Recibido de la Universidad Atlantida Argentina, en licenciatura en infromatica,con amplia experiencia en tecnología y soporte informático. Destaco por mi dominio en PROGRAMACION, CIENCIA DE DATOS y mi capacidad para resolver problemas técnicos de manera eficiente. Además, sobresalgo por mi habilidad para trabajar en equipo y adaptarme a entornos dinámicos.</p>
    </div>
  </template>
  
  <script>
  export default {
    name: 'CvSummary'
  }
  </script>
  
  <style scoped>
   h2 {
      color: aliceblue;
  }
  .cv-summary {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 50%;
    text-align: center;
  }
  </style>