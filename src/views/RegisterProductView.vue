<template>
    <div id="app">
      <Card />
    </div>
  </template>
  
  <script>
  import Card from '../components/CadastrarProdutosComponent.vue';
  
  export default {
    name: 'App',
    components: {
      Card
    }
  };
  </script>
  
  <style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  
  }
  </style>
  