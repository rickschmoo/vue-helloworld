<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorldRick test="123" message="hover 123"/>
    <HelloWorld msg="Welcome to Your Vue.js App 123"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HelloWorldRick from './components/HelloWorldRick.vue'

export default {
  name: 'app',
  components: {
    HelloWorld, HelloWorldRick
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
