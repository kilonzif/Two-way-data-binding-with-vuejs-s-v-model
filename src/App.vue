<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" style="width:100px; height:100px;">
    <Test msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import Test from './components/Test.vue'

export default {
  name: 'app',
  components: {
    Test
  }
}
</script>

<style>
img{
  align:center;
}
#app{
   font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  color: #2c3e50;
  margin-top: 60px;
  display: inline-block;
  margin-left:20%;
}
</style>
