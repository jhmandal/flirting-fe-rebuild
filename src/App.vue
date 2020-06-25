<template>
  <div id="app">
    <Main></Main>
  </div>
</template>

<script>
import Main from "./components/views/Main";

export default {
  name: "App",
  components: {
    Main,
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
