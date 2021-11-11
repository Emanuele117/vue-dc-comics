<template>
  <div id="app">
    <SiteHeader />

    <SiteMain />

    <footer></footer>
  </div>
</template>

<script>
import SiteHeader from "./components/SiteHeader.vue";
import SiteMain from "./components/SiteMain.vue";

export default {
  name: "App",
  components: {
    SiteHeader,
    SiteMain,
  },
};
/* import HelloWorld from "./components/HelloWorld.vue";


export default {
  name: "App",
  components: {
    HelloWorld,
  },
}; */
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
