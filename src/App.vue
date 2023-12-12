<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <PageTitle></PageTitle>
</template>

<script>
import PageTitle from "./components/PageTitle";

export default {
  name: "App",
  components: {
    PageTitle,
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
