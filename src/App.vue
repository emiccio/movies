<template>
  <div id="app">
    <Navbar/>
    <Contenido/>
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <Contenido msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
import Contenido from './components/Contenido.vue'
import Navbar from './components/Navbar.vue' 

export default {
  name: 'app',
  components: {
    Contenido,
    Navbar
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
