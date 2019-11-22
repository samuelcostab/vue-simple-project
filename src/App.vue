<template>
  <div id="app">
    <PaginaPrincipal msg="Primeira aplicação em Vue"/>
  </div>
</template>

<script>
import PaginaPrincipal from './components/PaginaPrincipal'

export default {
  name: 'app',
  components: {
    PaginaPrincipal
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
