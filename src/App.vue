<template>
  <NavBar msg="Welcome to Your Vue.js App"/>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <hr/>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <TableComponent title="Table title"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TableComponent from './components/TableComponent.vue'
import NavBar from './components/NavBar.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    TableComponent,
    NavBar
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
