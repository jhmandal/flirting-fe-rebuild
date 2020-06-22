<template>
  <div id="app">
    <MobileMain></MobileMain>
  </div>
</template>

<script>
import MobileMain from "./components/views/MobileMain";

export default {
  name: "App",
  components: {
    MobileMain,
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
