<template>
  <div id="app">
  <div class="container-fluid">
  <Cardbar />
    <br>
    <Littlecards class="mt-4" />
    <br>
    <Cardgraph class="mt-4"/>
  </div>
  </div>

</template>

<script>
import Littlecards from './components/Littlecards.vue'
import Cardbar from './components/Cardbar.vue'
import Cardgraph from './components/Cardgraph'

export default {
  name: 'App',
  components: {
    Littlecards,
    Cardbar,
    Cardgraph
  }
}
</script>

<style lang="scss">
*{
  background: #F7F8FA;
  margin:0;
  padding: 0;
   text-align: center;
}
#app {

  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
