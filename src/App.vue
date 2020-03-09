<template>
  <div id="app" class="app">
  <dropit-dashboard></dropit-dashboard>
  </div>
</template>

<script>
import homeComponent from './Home'

export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components : {
    'dropit-dashboard': homeComponent
  }
}
</script>

<style>
@import url("./assets/styles/app.min.css");

body {
  font-family: 'Roboto', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 100%;
  margin: auto;
}

</style>
