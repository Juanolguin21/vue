<template>
  <div class="cv-links">
    <h2>Links</h2>
    <a href="https://github.com/Juanolguin21" target="_blank" rel="noopener noreferrer" aria-label="GitHub">
      <img src="../assets/github.png" alt="GitHub" class="logo">
    </a>
    <a href="https://www.linkedin.com/in/juano34519842/" target="_blank" rel="noopener noreferrer" aria-label="LinkedIn">
      <img src="../assets/linkedin.png" alt="LinkedIn" class="logo">
    </a>
  </div>
</template>

<script>
export default {
  name: 'CvLinks'
}
</script>

<style scoped>
.cv-links {
  margin-bottom: 20px;
}

.cv-links a {
  display: inline-block; /* Ensure the link is clickable */
  cursor: pointer; /* Show a pointer cursor on hover */
  position: relative;
  z-index: 1; /* Ensure the link is above other elements */

}


.logo {
  width: 30px;
  height: 30px;
  margin-right: 10px;
  transition: opacity 0.3s ease;
}

.logo:hover {
  opacity: 0.7;
}
</style>