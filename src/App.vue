<template>
  <div id="app">
    <AppTitle />
    <HeroJumbo />
  </div>
</template>

<script>
import AppTitle from './components/AppTitle.vue'
import HeroJumbo from './components/HeroJumbo.vue'

export default {
  name: 'App',
  components: {
    AppTitle,
    HeroJumbo
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
