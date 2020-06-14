<template>
  <div>
    <p v-for="item in items" v-bind:key="item">
      {{item}}
    </p>
  </div>
</template>

<script>

export default {
  name: 'Topic',
  data() {
    return {
      items: ["Topic1","Topic2","Topic3","Topic4"]
    };
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
p{

  display: inline-block;
    
}
</style>
