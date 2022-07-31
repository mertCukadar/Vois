<template>
  <HelloWorld></HelloWorld>
  <introductionPage></introductionPage>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import introductionPage from "./components/intro_page.vue";
export default {
  name: "HomeView",
  components: {
    HelloWorld,
    introductionPage,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.Navigation {
  height: 30px;
}
</style>
