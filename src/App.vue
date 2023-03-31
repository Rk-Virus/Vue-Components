<template>
  <NavBar msg="Welcome to Your Vue.js App"/>
  <NavBar />
  <hr/>
  <HelloWorld msg="Welcome to Your Vue.js App" />
  <TableComponent title="Table title" />
  <!-- <NiceComponent /> -->
  <ToolTip/>
  <LabelProgess/>
  <FooterComponent />
  
  
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import FooterComponent from './components/FooterComponent.vue'
import TableComponent from './components/TableComponent.vue'
import ToolTip from './components/ToolTip.vue'
import LabelProgess from './components/LabelProgess.vue'



export default {
  name: 'App',
  components: {
    HelloWorld,
    TableComponent,
    FooterComponent,
    ToolTip,LabelProgess,

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
