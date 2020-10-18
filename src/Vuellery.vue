<template>
  <section id="pht__endpoint"></section>
</template>

<script>
import Photus from 'photus/dist/photus.min.js';
import 'photus/dist/css/main.css';

export default {
  name: 'Vuellery',
  props: {
    options: Object
  },

  mounted() {
    new Photus(this.options);
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
