<template>
  <div id="app">
  <Heading/>
  <calculator/>
  <Footer/>
  </div>
</template>

<script>
import Heading from './components/Heading.vue'
import calculator from './components/calculator.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Heading,
    calculator, 
    Footer
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
  margin-top: 40px;
}
</style>
