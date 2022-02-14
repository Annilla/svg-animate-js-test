<template>
  <div id="app">
    <valentines></valentines>
    <a href="https://www.vecteezy.com/free-vector/plant" target="blank">Plant Vectors by Vecteezy</a>
    <h1>Use <a href="https://github.com/svgdotjs/svg.js" target="blank">SVG.js</a></h1>
  </div>
</template>

<script>
import valentines from "./components/valentines-svg.vue";

export default {
  name: "App",
  components: { valentines },
};
</script>

<style>
body {
  margin: 0px;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
