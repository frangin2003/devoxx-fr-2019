<template>
  <v-app id="score-board">
    <!-- text-xs-center aligns text -->
    <v-container grid-list-md test-xs-center>
      <!-- align-center vertical aligns -->
      <v-layout row wrap align-center>
        <v-flex xs1>
          <img
            width="60"
            src="https://www.tinygraphs.com/labs/isogrids/hexa16/psg?theme=bythepool&numcolors=4&size=220&fmt=svg"
          >
        </v-flex>
        <v-flex xs3>
          <h2>PSG</h2>
        </v-flex>
        <v-flex xs4>
          <h1>0 - 0</h1>
        </v-flex>
        <v-flex xs3>
          <h2>MANCHESTER</h2>
        </v-flex>
        <v-flex xs1>
          <img
            width="60"
            src="http://tinygraphs.com/labs/isogrids/hexa16/manchester?theme=heatwave&numcolors=4&size=220&fmt=svg"
          >
        </v-flex>
      </v-layout>
    </v-container>
  </v-app>
</template>

<script>
export default {
  name: "ScoreBoard",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
