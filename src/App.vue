<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HomePage />
  </div>
</template>

<script>
import HomePage from './components/HomePage.vue'

export default {
  name: 'App',
  components: {
    HomePage
  }
}
</script>

<style>
  body{
      background-color: #0ef3e86d;
  }
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #054280;
    margin: 60px auto;
    max-width: 960px;  
  }
</style>
