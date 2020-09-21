<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/cropped-logo4.png">
    <HelloWorld msg="Alexander Aleshchenko"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  @import url("https://use.typekit.net/kyz0ydh.css");
  font-family: 'Bebas Neue Pro Bold', 'Bebas Neue Pro Book', 'Bebas Neue Pro', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
