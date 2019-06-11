<template>
<span id="app">
  <parrot></parrot>
  </span>
</template>
<script>
import Parrot from './components/Parrot.vue'

export default {
  name: 'app',
  components: {
    Parrot
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
