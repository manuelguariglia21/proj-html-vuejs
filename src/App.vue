<template>
  <div id="app">
    <HEADER />
    <MAIN />
    <FOOTER />
  </div>
</template>

<script>

import HEADER from './components/HEADER.vue';
import MAIN from './components/MAIN.vue';
import FOOTER from './components/FOOTER.vue';
export default {
  name: 'App',
  components: {
   HEADER,
   MAIN, 
   FOOTER
  }
}
</script>

<style lang="scss">
@import "./assets/style/vars.scss";
@import "./assets/style/generals.scss";

#app {
  color: $main-color;
}
</style>
