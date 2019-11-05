<template>
  <div id="app">
    <img src="./assets/logo.png">
    <one/>
    <router-view/>
  </div>
</template>

<script>
import One from './components/one'
export default {
  name: 'App',
  components:{
    One,
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>
