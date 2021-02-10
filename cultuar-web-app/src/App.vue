<template>
  <ModelViewer
    slug="alhambra/alhambra-v.1.0"
    description="Modelo 3D de la Alhambra"
  ></ModelViewer>
</template>

<script>
import ModelViewer from "./components/ModelViewer.vue";

export default {
  name: "App",
  components: {
    ModelViewer,
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
