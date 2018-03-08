<template>
<div id="calculator">
    <textarea disabled="disabled" readonly="readonly"></textarea>
    <div class="buttons">
        <button value="1">1</button>
        <button value="2">2</button>
        <button value="3">3</button>
        <button value="+">+</button>
        <button value="4">4</button>
        <button value="5">5</button>
        <button value="6">6</button>
        <button value="-">-</button>
        <button value="7">7</button>
        <button value="8">8</button>
        <button value="9">9</button>
        <button value="*">*</button>
        <button value="clear">clear</button>
        <button value="0">0</button>
        <button value="=">=</button>
        <button value="/">/</button>
    </div>
    <div id="history">

    </div>
</div>
</template>

<script>
export default {
  name: 'my1',
  data () {
    return {
      msg: 'Welcome to sss Vue.js App'
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
