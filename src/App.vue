<template>
  <!-- <h1>HELLO IM ALEX</h1> -->
  <static-background></static-background>
  <div class="sections__container">
    <bio-section></bio-section>
  </div>
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
</template>

<script>
import StaticBackground from './components/StaticBackground.vue';
import BioSection from './components/BioSection.vue';
// import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    StaticBackground,
    BioSection,
    // HelloWorld,
  },
};
</script>

<style>
@font-face {
  font-family: jeko;
  src: url("../public/fonts/Jeko-Extra-Bold.ttf"), url("../public/fonts/Jeko-Regular.ttf");
}
body{
  margin: 0;
}
#app {
  font-family: jeko, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.sections__container {
  width: calc(100vw - 120px);
  margin-left: 50px;
  margin-top: 100px;
  padding: 10px;
}
section{
  min-height: calc(100vh - 150px);
}
</style>
