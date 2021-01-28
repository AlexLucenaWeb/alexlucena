<template>
  <section>
    <h2>{{ work }}</h2>
    <div class="work__container">
      <div class="work__photo">
        <div class="photo__img">
          <img src="../../public/images/thai-photo.jpg" alt="Thai football player" />
        </div>
        <p>
          In 2016 I decided to take a step forwards as <span>photographer</span>
          and I moved to Thailand to collaborate with two spanish NGOs.
          <br />
          <a href="https://www.playonside.org/" target="_blank"
            ><span class="white">{{ playonside }}</span></a
          >
          and
          <a href="https://www.colaborabirmania.org/" target="_blank"
            ><span class="white">{{ colabora }}</span></a
          >
          <br />
          There I could develop amazing audiovisual projects
        </p>
      </div>
      <div class="work__illsutration">
        <img src="../../public/images/thai-photo.jpg" alt="Thai football player" />
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed rutrum malesuada velit, in
          rhoncus lorem faucibus quis. Maecenas ullamcorper porttitor diam. Class aptent taciti
          sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Donec id luctus
          lectus. Fusce laoreet libero diam, sed malesuada purus dignissim ac. Pellentesque dapibus
          volutpat luctus. Fusce finibus faucibus est, vel posuere diam aliquet quis. Aliquam erat
          volutpat. Quisque euismod pretium orci sed tincidunt. Aliquam erat volutpat. Nunc mattis
          sapien arcu, eget sodales neque ornare sed. Praesent bibendum porttitor eros eget iaculis.
          Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </p>
      </div>
      <div class="work__web">
        <img src="../../public/images/thai-photo.jpg" alt="Thai football player" />
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed rutrum malesuada velit, in
          rhoncus lorem faucibus quis. Maecenas ullamcorper porttitor diam. Class aptent taciti
          sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Donec id luctus
          lectus. Fusce laoreet libero diam, sed malesuada purus dignissim ac. Pellentesque dapibus
          volutpat luctus. Fusce finibus faucibus est, vel posuere diam aliquet quis. Aliquam erat
          volutpat. Quisque euismod pretium orci sed tincidunt. Aliquam erat volutpat. Nunc mattis
          sapien arcu, eget sodales neque ornare sed. Praesent bibendum porttitor eros eget iaculis.
          Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </p>
        <img src="../../public/images/thai-photo.jpg" alt="Thai football player" />
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed rutrum malesuada velit, in
          rhoncus lorem faucibus quis. Maecenas ullamcorper porttitor diam. Class aptent taciti
          sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Donec id luctus
          lectus. Fusce laoreet libero diam, sed malesuada purus dignissim ac. Pellentesque dapibus
          volutpat luctus. Fusce finibus faucibus est, vel posuere diam aliquet quis. Aliquam erat
          volutpat. Quisque euismod pretium orci sed tincidunt. Aliquam erat volutpat. Nunc mattis
          sapien arcu, eget sodales neque ornare sed. Praesent bibendum porttitor eros eget iaculis.
          Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      work: '<work>',
      playonside: '<www.playonside.org>',
      colabora: '<www.colaborabirmania.org>',
    };
  },
};
</script>

<style scoped>
.white {
  color: white;
}
a {
  text-decoration: none;
}
.photo__img {
  width: calc(100vw - 117px);
  height: 300px;
  overflow: hidden;
}
.photo__img img {
  width: 100%;
}
</style>
