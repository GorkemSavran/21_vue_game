<template>
  <div id="app">
    <Game></Game>
  </div>
</template>

<script>
import Game from "./components/Game";
export default {
  name: "app",
  components: {
    Game
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
