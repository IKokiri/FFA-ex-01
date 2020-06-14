<template>
  <div class="bg">
    <Topic/>
    <Logo/>
    <Busca/>
    <Nav/>
  </div>
</template>

<script>

import Logo from './Logo.vue'
import Busca from './Busca.vue'
import Nav from './Nav.vue'
import Topic from './Topic.vue'

export default {
  name: 'Cabecalho',
  components: {
    Logo,
    Busca,
    Nav,
    Topic
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.bg{
  background-color: cyan;
}
</style>