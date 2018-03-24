<template>
  <div id="app">
    <Navbar/>
    <Jumbotron/>
    <HelloWorld/>
  </div>
</template>

<script>

import HelloWorld from './components/HelloWorld';
import Navbar from './components/Navbar';
import Jumbotron from './components/Jumbotron';

export default {
  name: 'App',
  components: {
    Navbar,
    Jumbotron,
    HelloWorld,
  },
};
</script>

<style>
body, html {
    height: 100%;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
