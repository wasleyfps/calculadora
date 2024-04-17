<template>
  <div id="app">
    <h1>Calculadora</h1>
    <Calculator />
    <footer><p>Projeto desenvolvido por <a href="https://www.wasley.com.br/">Wasley Carvalho</a>  ❤️☕</p></footer>
  </div>
</template>

<script>
import Calculator from './components/CalculatorComponent.vue';

export default {
  name: 'App',
  components: {
    Calculator
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

footer {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  padding: 10px;
  background-color: #f5f5f5;
  text-align: center;
  border-top: 1px solid #ccc;
  color: #333;
}
</style>
