<template>
  <div id="app">
    <mi-tabla :array="numbers" :class="newClass" :boolean="boolean"/>
  </div>
</template>

<script>
import './components/MiTabla.css'
import MiTabla from './components/MiTabla.vue'

export default {
  name: 'App',
  components: {
    MiTabla
  },
  data: function () {
    return {
      numbers:[1,2,34,4],
      newClass:"table-info",
      boolean:true 
    }
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
