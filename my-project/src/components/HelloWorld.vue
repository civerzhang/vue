<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Essential Li11nks</h2>
    <a href="./html/info.html">info</a>
    <router-link to="/bar">Go to Bar</router-link>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome111 to sss Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
