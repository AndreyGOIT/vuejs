<template>
  <div id="App">
    <ButtonT>Click me</ButtonT>
  </div>
</template>

<script>
import ButtonT from "./components/ButtonTempl.vue";

export default {
  name: "App",
  components: {
    ButtonT,
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
