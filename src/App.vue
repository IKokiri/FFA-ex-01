<template>
  <div id="app">
    
    <Logo/>
    <Cabecalho/>
    <Nav/>
    <Artigo/>
    <Sidebar/>
    
  </div>
</template>

<script>
import Logo from './components/Logo.vue'
import Cabecalho from './components/Cabecalho.vue'
import Nav from './components/Nav.vue'
import Artigo from './components/Artigo.vue'
import Sidebar from './components/Sidebar.vue'

export default {
  name: 'App',
  components: {
    Logo,
    Cabecalho,
    Nav,
    Artigo,
    Sidebar
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
