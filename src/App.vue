<template>
  <div class="body">
    <Nav/>
    <div class="container">
      <router-view/>
    </div>
  </div>
</template>

<script>
import Nav from './components/partials/Nav.vue'

import '../node_modules/materialize-css/dist/css/materialize.min.css';
import '../node_modules/materialize-css/dist/js/materialize.min.js';

export default {
  name: "App",
  components: {
    Nav
  }
};
</script>

<style lang="scss">
  body {
  background: linear-gradient(to right bottom, gray, lightgray);
  height: 100vh;
}
</style>
