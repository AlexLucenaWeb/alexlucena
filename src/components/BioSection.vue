<template>
  <section>
    <h2>{{ bio }}</h2>
    <div class="bio__container">
      <p class="bio__bio">
        I am Alex, a spanish <span class="white">web developer</span> based in
        <span class="white">Dublin</span>. <br />After several years working in the education
        sistem, I decided to move forward and find my place in the web technologies area. I have
        been working to improve my skills and develop my own projects to turn this passion into a
        profesion.
      </p>
      <img class="bio__img" src="../../public/images/alex-photo.png" alt="Alex Lucena photo" />
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      bio: '<bio>',
    };
  },
};
</script>

<style scoped>
.bio__container {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  min-height: calc(100vh - 150px);
}
.bio__img {
  width: 250px;
  height: 250px;
}
.bio__bio {
  max-width: 50%;
}
.white {
  color: white;
}

@media only screen and (min-width: 1600px) {
  p {
    font-size: 3em;
  }
  .bio__img {
    width: 400px;
    height: 400px;
  }
}
</style>
