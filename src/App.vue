<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <pageHeader/>
    <pageBody/>
    <pageFooter/>
  </div>
</template>

<script>
import pageHeader from "@/components/pageHeader.vue";
import pageBody from "@/components/pageBody.vue";
import pageFooter from "@/components/pageFooter.vue";

export default {
  name: 'App',
  components: {
    pageHeader,
    pageBody,
    pageFooter

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
