<template>
  <div id="App">
    <h1>{{ title }}</h1>
    <ButtonT @click="increment">Click me</ButtonT>
  </div>
</template>

<script>
import ButtonT from "./components/ButtonTempl.vue";

export default {
  name: "App",
  components: {
    ButtonT,
  },
  data() {
    return {
      amountOfClicks: 0,
    };
  },
  computed: {
    title() {
      return `Amount of clicks ${this.amountOfClicks}`;
    },
  },
  methods: {
    increment() {
      return (this.amountOfClicks += 1);
    },
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
