<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <SwiperCarousel />
</template>

<script>
import SwiperCarouselVue from "./components/SwiperCarousel.vue";
export default {
  name: "App",
  components: {
    SwiperCarousel: SwiperCarouselVue,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
