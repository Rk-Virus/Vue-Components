<template>
  <NavBar msg="Welcome to Your Vue.js App"/>
  <NavBar />
  <hr/>
  <SkeletonBar />
  <HelloWorld msg="Welcome to Your Vue.js App" />
  <TableComponent title="Table title" />
  <!-- <NiceComponent /> -->
  <CardLabel/>
  <AccordianLabel/>
  <snackBar/>
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
import SkeletonBar from './components/SkeletonBar.vue'
import snackBar from './components/snackBar.vue'
import CardLabel from './components/CardLabel.vue'
import AccordianLabel from './components/AccordianLabel.vue'



export default {
  name: 'App',
  components: {
    HelloWorld,
    TableComponent,
    FooterComponent,
    ToolTip,LabelProgess,SkeletonBar,snackBar,CardLabel,AccordianLabel

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
