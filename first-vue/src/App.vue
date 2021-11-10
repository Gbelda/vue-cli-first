<template>
  <div id="app">
    <mytitle />
    <jumboimg />
  </div>
</template>

<script>
import mytitle from "./components/title.vue";
import jumboimg from "./components/hero.vue";
export default {
  name: "App",
  components: {
    mytitle,
    jumboimg,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
