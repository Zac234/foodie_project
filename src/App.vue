<template>
  <div id="app">
    
  </div>
</template>

<script>
import clientHeadVue from './components/clientHead.vue';

import clientMainVue from './components/clientMain.vue';
import clientFootVue from './components/clientFoot.vue';
export default {
  name: 'App',
  components: {
    clientHeadVue,
    clientMainVue,
    clientFootVue
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
