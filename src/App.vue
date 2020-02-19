<template>
  <div id="app">
    
    <Logo/>
    <Cabecalho nav/>    
    <Busca/>
    <Nav/>
    <Artigo/>
    <Sidebar/>
    
  </div>
</template>

<script>
import Cabecalho from './components/Cabecalho.vue'
import Artigo from './components/Artigo.vue'
import Sidebar from './components/Sidebar.vue'

export default {
  name: 'App',
  components: {
    Cabecalho,
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
}
</style>
