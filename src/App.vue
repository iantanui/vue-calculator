<template>
  <body>

    <div id="#app">

      <h1>Welcome to my Calculator</h1>

      <calculator />
    </div>
    
  </body>
</template>

<script>
import Calculator from './components/Calculator.vue';

export default {
  name: 'App',
  components: {
    Calculator
  }
}

</script>

<style>
  body {
    background: darkslategray;
  }
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1 {
  position: relative;
  font-size: 50px;
  color: #4aa748;
}
</style>
