<template>
    <div class="cv-header">
      <img src="../assets/1000188342.jpg" alt="Foto de perfil" class="profile-image">
      <h1>Juan Manuel Olguin</h1>
      <p>7107, Buenos Aires</p>
      <p>+5492246441913</p>
      <p>waltercito100@hotmail.com</p>
      <p>Argentino</p>
    </div>
  </template>
  
  <script>
  export default {
    name: 'CvHeader'
  }
  </script>
  
  <style scoped>
   h1{
      color: aliceblue;
  }
  .cv-header {
    text-align: center;
    margin-bottom: 20px;
    margin-top: 50px;
  }

  p {
    color: brown;
    font-weight: bold;
  }
  
  .profile-image {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 10px;
  }
  </style>