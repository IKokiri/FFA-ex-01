<template>
  <img src="logo.png">
</template>

<script>
export default {
  name: 'Logo',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 img{
   width:100px;
 }
</style>