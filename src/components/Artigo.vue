<template>
  <div class="artigo">
    <p  v-for="item in items" v-bind:key="item">
      {{item}}
    </p>

  </div>
  
</template>

<script>
export default {
  name: 'Artigo',
  data() {
    return {
      items: [" sadasd asd asd sda Artigo 1","kljljl j ljk l jl jl kjljl Artigo 2"," poi pou opiu pou opu op upArtigo 3"]
    };
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

 p {
        width: 20%;
        display: inline-block;
        background-color: red;
        font-size: 3vw;
        text-align: center;
        padding: 5vw 0vw 5vw 0vw;
        min-width:40vw;
    }
</style>
