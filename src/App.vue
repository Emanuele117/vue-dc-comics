<template>
  <div id="app">
    <SiteHeader />

    <SiteMain />

    <SiteFooter />
  </div>
</template>

<script>
import SiteHeader from "./components/SiteHeader.vue";
import SiteMain from "./components/SiteMain.vue";
import SiteFooter from "./components/SiteFooter.vue";

export default {
  name: "App",
  components: {
    SiteHeader,
    SiteMain,
    SiteFooter,
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
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
