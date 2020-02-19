<template>
  <div>
   <input type="search">
  </div>
</template>

<script>
export default {
  name: 'Busca',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
input[type=search] { 
	color: red;  
	text-align: right;
	cursor: pointer;
	display: block; 
	width: 100%; 
	letter-spacing: 4px;        
	text-shadow: 0 0 2px black;       
	word-spacing: 20px;               
}
</style>
