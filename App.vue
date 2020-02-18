<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <dropdown msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import dropdown from './components/dropdown.vue'

export default {
  name: 'App',
  components: {
    dropdown
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
