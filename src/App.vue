<template>
  <div id="app">
    <img class="logo" alt="Vue logo" src="./assets/boolean.jpg">
    <Hero />
    <Titolo />
  </div>
</template>

<script>
import Titolo from './components/primaApp.vue'
import Hero from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    Titolo,
    Hero,
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

.logo{
  height: 150px;
}

</style>
