<template>
  <section id="pht__endpoint"></section>
</template>

<script>
import Photus from 'photus/dist/photus.js';
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
