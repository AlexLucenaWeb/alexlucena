<template>
  <h1>HELLO IM ALEX</h1>
  <static-background></static-background>
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <p>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed rutrum malesuada velit, in rhoncus
    lorem faucibus quis. Maecenas ullamcorper porttitor diam. Class aptent taciti sociosqu ad litora
    torquent per conubia nostra, per inceptos himenaeos. Donec id luctus lectus. Fusce laoreet
    libero diam, sed malesuada purus dignissim ac. Pellentesque dapibus volutpat luctus. Fusce
    finibus faucibus est, vel posuere diam aliquet quis. Aliquam erat volutpat. Quisque euismod
    pretium orci sed tincidunt. Aliquam erat volutpat. Nunc mattis sapien arcu, eget sodales neque
    ornare sed. Praesent bibendum porttitor eros eget iaculis.

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed rutrum malesuada velit, in rhoncus
    lorem faucibus quis. Maecenas ullamcorper porttitor diam. Class aptent taciti sociosqu ad litora
    torquent per conubia nostra, per inceptos himenaeos. Donec id luctus lectus. Fusce laoreet
    libero diam, sed malesuada purus dignissim ac. Pellentesque dapibus volutpat luctus. Fusce
    finibus faucibus est, vel posuere diam aliquet quis. Aliquam erat volutpat. Quisque euismod
    pretium orci sed tincidunt. Aliquam erat volutpat. Nunc mattis sapien arcu, eget sodales neque
    ornare sed. Praesent bibendum porttitor eros eget iaculis.

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed rutrum malesuada velit, in rhoncus
    lorem faucibus quis. Maecenas ullamcorper porttitor diam. Class aptent taciti sociosqu ad litora
    torquent per conubia nostra, per inceptos himenaeos. Donec id luctus lectus. Fusce laoreet
    libero diam, sed malesuada purus dignissim ac. Pellentesque dapibus volutpat luctus. Fusce
    finibus faucibus est, vel posuere diam aliquet quis. Aliquam erat volutpat. Quisque euismod
    pretium orci sed tincidunt. Aliquam erat volutpat. Nunc mattis sapien arcu, eget sodales neque
    ornare sed. Praesent bibendum porttitor eros eget iaculis.

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed rutrum malesuada velit, in rhoncus
    lorem faucibus quis. Maecenas ullamcorper porttitor diam. Class aptent taciti sociosqu ad litora
    torquent per conubia nostra, per inceptos himenaeos. Donec id luctus lectus. Fusce laoreet
    libero diam, sed malesuada purus dignissim ac. Pellentesque dapibus volutpat luctus. Fusce
    finibus faucibus est, vel posuere diam aliquet quis. Aliquam erat volutpat. Quisque euismod
    pretium orci sed tincidunt. Aliquam erat volutpat. Nunc mattis sapien arcu, eget sodales neque
    ornare sed. Praesent bibendum porttitor eros eget iaculis.

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed rutrum malesuada velit, in rhoncus
    lorem faucibus quis. Maecenas ullamcorper porttitor diam. Class aptent taciti sociosqu ad litora
    torquent per conubia nostra, per inceptos himenaeos. Donec id luctus lectus. Fusce laoreet
    libero diam, sed malesuada purus dignissim ac. Pellentesque dapibus volutpat luctus. Fusce
    finibus faucibus est, vel posuere diam aliquet quis. Aliquam erat volutpat. Quisque euismod
    pretium orci sed tincidunt. Aliquam erat volutpat. Nunc mattis sapien arcu, eget sodales neque
    ornare sed. Praesent bibendum porttitor eros eget iaculis.
  </p>
</template>

<script>
import StaticBackground from './components/StaticBackground.vue';
// import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    StaticBackground,
    // HelloWorld,
  },
};
</script>

<style>
@font-face {
  font-family: jeko;
  src: url("../public/fonts/Jeko-Extra-Bold.ttf"), url("../public/fonts/Jeko-Regular.ttf");
}
#app {
  font-family: jeko, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
p{
  font-size: 5rem;
}
static-background{
  position: fixed;
  top: 0px;
  left: 0px;
}
</style>
