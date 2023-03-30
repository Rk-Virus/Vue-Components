<template>
  <NavBar msg="Welcome to Your Vue.js App"/>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <NavBar />
  <hr/>
  <HelloWorld msg="Welcome to Your Vue.js App" />
  <TableComponent title="Table title" />
  <NiceComponent />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TableComponent from './components/TableComponent.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    TableComponent
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
