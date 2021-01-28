<template>
  <section>
    <h2>{{ work }}</h2>
    <div class="work__container">
      <div class="work__photo">
        <div class="photo__img">
          <img src="../../public/images/thai-photo.jpg" alt="Burmese football player" />
        </div>
        <div class="photo__content">
          <div class="content__p">
            <p>
              In 2016 I decided to take a step forwards as <span class="white">photographer</span>
              and I moved to Thailand to collaborate with two spanish NGOs.
            </p>
            <p>
              <a href="https://www.playonside.org/" target="_blank"
                ><span class="white">{{ playonside }}</span></a
              >
              and
              <a href="https://www.colaborabirmania.org/" target="_blank"
                ><span class="white">{{ colabora }}</span></a
              >
            </p>
            <p>
              There I could develop amazing audiovisual projects and grow up
              profesianl and personaly.
            </p>
          </div>
          <img
            class="content__img"
            src="../../public/images/thai-photo-2.jpg"
            alt="Burmese child"
          />
        </div>
      </div>
      <div class="work__illsutration">
        <img src="../../public/images/book-photo.jpg" alt="Illustration of Daddy Mouse" />
        <p>
          Back in Spain,
          <span class="white">Illustrator</span>
           in cooperation with
          <span class="white"><a href="https://lamusicaytu.com/" target="_blank">{{ musica }}</a> </span>
          I illustrated my first children's tale book, "Los Ratones y la Lluvia"
          and develop a successful crowdfunding to make this project a reallity.
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
      playonside: '<playonside>',
      colabora: '<colaborabirmania>',
      musica: '<la música y tú>',
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
p{
  font-weight: lighter;
  font-size:1.7em ;
}
/* Photographer */
.photo__img {
  width: calc(100vw - 117px);
  height: calc(100vh - 100px);
  overflow: hidden;
}
.photo__img img {
  width: 100%;
}
.photo__content {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  padding: 50px;
}
.content__img {
  width: 400px;
}
.content__p{
  width: 37vw;
}
</style>
