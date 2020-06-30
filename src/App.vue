<template>
  <div id="app">
    <Main></Main>
    <!-- <Singular></Singular> -->
  </div>
</template>

<script>
import Main from "./components/views/Main";
// import Singular from "./components/views/Singular";

export default {
  name: "App",
  components: {
    Main,
    // Singular
  },
};
</script>

<style>
#app {
  font-family: Roboto, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>