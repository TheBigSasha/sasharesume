<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>
      Download a resume!<br>
    </h2>
    <h3>PDF</h3>
    <ul>
      <li><a href="https://drive.google.com/file/d/1p2lyQC9Ks4M3D5pNWrqRKXONIAaJVBAb/view?usp=sharing" target="_blank" rel="noopener">Boring Version</a></li>
      <li><a href="https://drive.google.com/file/d/1p2lyQC9Ks4M3D5pNWrqRKXONIAaJVBAb/view?usp=sharing" target="_blank" rel="noopener">Pretty Version</a></li>
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
    font-size: 72pt;
    font-family: "Bebas Neue Pro Bold",sans-serif;
  }
  p{
    font-size: 1pc;
  }
  h2{
    font-size: 3pc;
    font-family: "Bebas Neue Pro Light",sans-serif;
  }
h3 {
  margin: 40px 0 0;
  font-size: 3pc;
}
ul {
  list-style-type: none;
  padding: 0;
  font-size: 2pc;
}
li {
  display: inline-block;
  margin: 0 10px;
  font-size: 2pc;
}
a {
  color: #42b983;
}
</style>
