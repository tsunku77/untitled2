<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
<!--    //<HelloWorld msg="Welcome to Your Vue.js App"/>-->
    <Kjh></Kjh>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Kjh from "@/components/Kjh";

export default {
  name: 'App',
  components: {
    Kjh,
    //HelloWorld
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
