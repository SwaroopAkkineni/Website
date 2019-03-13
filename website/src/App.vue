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
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  background: linear-gradient(45deg, #17ead9, #6078ea);
  height: 100vh;
  margin: 0;
  background-attachment: fixed;
}
</style>
