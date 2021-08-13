<template>
  <div id="app">
    <Props :nom="{ first: 'Tactic', last: 'Rayan' }"></Props>
  </div>
</template>

<script>
import Props from './components/Props.vue'

export default {
  name: 'App',
  components: {
    Props
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
