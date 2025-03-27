<template>
    <div class="hello">
      <h1>{{ msg }}</h1>
      <button @click="sayHello">Click Me!</button>
    </div>
  </template>
  
  <script>
  export default {
    name: 'HelloWorld',
    props: {
      msg: String
    },
    methods: {
      sayHello() {
        alert('¡Hola desde Vue.js!');
      }
    }
  }
  </script>
  
  <style scoped>
  h1 {
    color: #42b983;
  }
  </style>