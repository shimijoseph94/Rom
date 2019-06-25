<template>
  <div id="app">
    <app-header/>
    <router-view/>
    <Footer/>
  </div>
</template>

<script>
import AppHeader from '../src/components/Navbar'
import Footer from '../src/components/Footer'
export default {
  name: 'App',
   components: {
    AppHeader,Footer
  },
  
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 20px;
}
</style>
