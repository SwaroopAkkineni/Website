<template>
  <div class="mySite">
    <p>Swaroop Akkineni</p>
    <p>Software Engineer. Runner. Gamer.</p>
    <a href="https://www.linkedin.com/in/swaroop-akkineni">
      <img src="../assets/linkedin.png">
    </a>
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

<style>
  .mySite {
    align: left;
    /* margin-top: 10%; */
    margin-left: 5%;
  }

  .image {
    background-repeat: no-repeat;
    background-position: 50%;
    border-radius: 50%;
    width: 200px;
    height: 200px;
  }
</style>
