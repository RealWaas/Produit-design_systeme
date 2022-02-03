<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <Boutton/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Boutton from './components/Boutton.vue'

import './assets/styles/style.css';

export default {
  name: 'App',
  components: {
    HelloWorld,
    Boutton
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
