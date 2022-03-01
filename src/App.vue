<template>
  <div>
    <FindLogos />
  </div>
</template>

<script>
import FindLogos from './components/FindLogos.vue'

export default {
  name: 'App',
  components: {
    FindLogos
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
