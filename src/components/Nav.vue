<template>
  <ul>
    <li v-for="item in items" v-bind:key="item">
      <a href="#">{{item}}</a>
    </li>
  </ul>
</template>

<script>
export default {
  name: "Nav",
  props: {
  },
  data() {
    return {
      items: ["Nav 1","Nav 2","Nav 3","Nav 4"]
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change the link color to #111 (black) on hover */
li a:hover {
  background-color: #111;
}
</style>