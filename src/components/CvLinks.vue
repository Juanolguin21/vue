<template>
    <div class="cv-links">
      <h2>Links</h2>
      <a href="https://github.com/Juanolguin21">GitHub</a><br>
      <a href="https://www.linkedin.com/in/juano34519842/">LinkedIn</a>
    </div>
  </template>
  
  <script>
  export default {
    name: 'CvLinks'
  }
  </script>
  
  <style scoped>
   h2 {
      color: aliceblue;
  }
  .cv-links {
    margin-bottom: 50px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 50%;
    color: brown;
  }
  </style>