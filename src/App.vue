<template>
  <!-- <counter :title="'Nacimientos'" /> -->
  <indecition/>
</template>

<script>

import Counter from './components/Counter.vue';
import Indecition from './components/Indecision.vue';

export default {
  name: 'App',
  components: {
    Counter,
    Indecition
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
