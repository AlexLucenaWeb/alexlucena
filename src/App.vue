<template>
  <!-- <h1>HELLO IM ALEX</h1> -->
  <static-background></static-background>
  <div class="sections__container">
    <animation-section></animation-section>
    <bio-section></bio-section>
    <work-section></work-section>
    <contact-section></contact-section>
  </div>
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
</template>

<script>
import StaticBackground from './components/StaticBackground.vue';
import BioSection from './components/BioSection.vue';
import WorkSection from './components/WorkSection.vue';
import ContactSection from './components/ContactSection.vue';
import AnimationSection from './components/AnimationSection.vue';

export default {
  name: 'App',
  components: {
    StaticBackground,
    BioSection,
    WorkSection,
    ContactSection,
    AnimationSection,
  },
};
</script>

<style>
@font-face {
  font-family: jeko;
  src: url("../public/fonts/Jeko-Extra-Bold.ttf"), url("../public/fonts/Jeko-Regular.ttf"),
    url("../public/fonts/Jeko-Light.ttf");
}
body {
  margin: 0;
}
#app {
  font-family: jeko, sans-serif;
  /* font-weight: normal; */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.sections__container {
  width: calc(100vw - 117px);
  margin-left: 50px;
  margin-top: 50px;
  padding-bottom: 20px;
}
section {
  min-height: calc(100vh - 100px);
}
h2{
    font-weight: bolder;
    color: #ffffff;
    font-size: 5em;
    margin: 0;
}
p {
  font-size: 2em;
  font-weight: lighter;
  text-align: justify;
}
</style>
