<template>
    <div class="cv-languages">
      <h2>Idiomas</h2>
      <p>Español: C2 (Experto)</p>
      <p>Inglés: C1 (Avanzado)</p>
      <p>Portugués: B2 (Intermedio alto)</p>
    </div>
  </template>
  
  <script>
  export default {
    name: 'CvLanguages'
  }
  </script>
  
  <style scoped>
  h2 {
      color: aliceblue;
  }
  .cv-languages {
    margin-bottom: 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 50%;
  }
  </style>