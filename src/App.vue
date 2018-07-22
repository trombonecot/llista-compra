<template>
  <div id="app">
    <h1>Llista de la compra</h1>
    <LlistaCompra />
  </div>
</template>

<script>
import LlistaCompra from './views/LlistaCompra.vue'

export default {
  name: 'app',
  components: {
    LlistaCompra
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
