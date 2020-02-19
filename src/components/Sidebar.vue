<template>
 <ul>
    <li v-for="item in items" v-bind:key="item">
      <a href="#">{{item}}</a>
    </li>
  </ul>
</template>

<script>
export default {
  name: 'Sidebar',
  data() {
    return {
      items: ["Section 1","Section 2","Section 3","Section 4","Section 5","Section 6"]
    };
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
