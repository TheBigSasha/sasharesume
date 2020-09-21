<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>
      Download a PDF!<br>
    </h2>
    <ul>
      <li><a href="https://drive.google.com/file/d/1g-rDvIiuhZMlYQ8VcBUKafpNguKCLWoA/view?usp=sharing" target="_blank" rel="noopener">Short Version</a></li>
      <li><a href="https://drive.google.com/file/d/1gqgy4pVJbob3M_b_wlT5WEzpItm3LqUW/view?usp=sharing" target="_blank" rel="noopener">Full Version</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1{
    font-size: 45pt;
    font-family: "Bebas Neue Pro Bold",sans-serif;
    font-optical-sizing: auto;
  }
  p{
    font-size: 24pt;
  }
  h2{
    font-size: 40pt;
    margin: auto;
    font-family: "Bebas Neue Pro Thin",sans-serif;
    font-optical-sizing: auto;
  }
h3 {
  margin: 10px 0 0;
  font-size: 3pc;
}
ul {
  list-style-type: none;
  padding: 0;
  font-size: 3pc;
}
li {
  display: inline-block;
  margin: 0 10px;
  font-size: 30pt;
}
a {
  color: #42b983;
}
</style>
