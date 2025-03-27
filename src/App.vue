<template>
  <div id="cv-app">
    <CvHeader />
    <CvSummary />
    <CvExperience />
    <CvEducation />
    <CvSkills />
    <CvLanguages />
    <CvLinks />
  </div>
</template>

<script>
import CvHeader from './components/CvHeader.vue';
import CvLinks from './components/CvLinks.vue';
import CvSummary from './components/CvSummary.vue';
import CvExperience from './components/CvExperience.vue';
import CvEducation from './components/CvEducation.vue';
import CvSkills from './components/CvSkills.vue';
import CvLanguages from './components/CvLanguages.vue';

export default {
  name: 'App',
  components: {
    CvHeader,
    CvSummary,
    CvExperience,
    CvEducation,
    CvSkills,
    CvLanguages,
    CvLinks
  }
}
</script>

<style>
#cv-app {
  font-family: 'Arial', sans-serif;
  margin: 50px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  min-height: 100vh;
  position: relative; /* Necesario para posicionar el pseudo-elemento */
  z-index: -1; /* Asegura que el contenido esté encima del pseudo-elemento */
  border-radius: 2%;

}

#cv-app::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-position: center;
  background-color: grey; /* Capa semitransparente blanca */
  z-index: -1; /* Posiciona el pseudo-elemento detrás del contenido */
  border-radius: 2%;

}
body {
  background-image: url('../src/assets/1.png');
}
</style>