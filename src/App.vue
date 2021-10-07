<template>
  <div class="container">
    <ImageSwiper />
  </div>
</template>

<script>
import ImageSwiper from "./components/ImageSwiper.vue";

export default {
  name: "App",
  components: {
    ImageSwiper,
  },
};
</script>

<style lang="scss">
body {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  display: flex;
  justify-content: center;
}

.container {
  margin-top: 50px;
  background-color: #eee;
  width: 550px;
  height: 630px;
}
</style>
