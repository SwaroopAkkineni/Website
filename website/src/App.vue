<template>
  <div id="app">
    <mySite/>
  </div>
</template>

<script>
import mySite from './components/mySite.vue';

export default {
  name: 'app',
  components: {
    mySite,
  },
};
</script>

<style>
  #app {
    font-family: 'Avenir', Georgia, Arial, sans-serif;
    background: #fff;
    margin: 0 !important;
    padding: 0;
    background-repeat: no-repeat;
  }
  html, body, #app {
    padding: 0;
    margin: 0;
    min-height: 100% !important;
    height: 100%;
  }
</style>
