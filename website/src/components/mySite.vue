<template>
  <div class="main">
    <div class="leftBar">
      <p>Swaroop Akkineni</p>
      <p>Poop</p>
    </div>
    <!-- <a href="https://www.linkedin.com/in/swaroop-akkineni">
      <img src="../assets/linkedin.png">
    </a> -->
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
};

</script>

<style scoped>
  .main {
    padding: 0;
    margin: 0;
    min-height: 100% !important;
    height: 100%;
  }
  .leftBar {
    background-position: left 0px;
    background-color: #59ABE3;
    width: 30%;
    clear: both;
    display: block;
    float: left;
    height: 100%;
  }
</style>
