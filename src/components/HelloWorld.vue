<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div id="example-1">
</div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      activeColor: 'blue',
      fontSize: 30
    }
  },
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello{
  color: rgb(0, 98, 116);
  font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
}
h3 {
  margin: 40px 0 0;
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
  color: #383428;
}
</style>