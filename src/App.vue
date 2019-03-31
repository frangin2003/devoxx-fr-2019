<template>
  <div id="app">
      <ScoreBoard/>
  </div>
</template>

<script>
import Vue from "vue";
import Vuetify from "vuetify";
import ScoreBoard from "./components/ScoreBoard";

Vue.use(Vuetify);

export default {
  name: "App",
  components: {
    ScoreBoard
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
