<template>
  <div class="artigo">
    <p  v-for="item in items" v-bind:key="item">
      <Imagem/>
      {{item}}
    </p>

  </div>
  
</template>

<script>
import Imagem from './Imagem.vue'
export default {
  name: 'Artigo',
  components: {
    Imagem
  },
  data() {
    return {
      items: ["sadasd asd asd sda asdasd asd asd asd asd asd asd sad sad sasadasd asd asd sda asdasd asd asd asd asd asd asd sad sad sasadasd asd asd sda asdasd asd asd asd asd asd asd sad sad sa Artigo 1",
              "kljljl j ljk l jl jl kjlj asd asd asd asd asd asd asd asd al Artigokljljl j ljk l jl jl kjlj asd asd asd asd asd asd asd asd al Artigokljljl j ljk l jl jl kjlj asd asd asd asd asd  Artigo 2",
              "asd asd asd asd asd asd asd asd as dsapoi pou op pou opu op upArtigoasd asd asd asd asd asd asd asd as dsapoi pou op pou opu op upArtigoasd asd asd asd asd asd asd asd as dsapoi pupArtigo 3"]
    };
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 p {
        width: 20%;
        display: inline-block;
       
    }
</style>
