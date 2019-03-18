<template>
  <div class="main">
    <div class="leftBar">
      <div class="text">
        <div class="imageDiv">
          <img class="resize" src="../assets/image3.jpg"></img>
        </div>
        <div class="intro">
          <p class="bold">Hello!</p>
          <p>I'm Swaroop Akkineni</p>
          <p>I like to run and solve challenging problems </p>
        </div>
        <div class="contact">
          <a href="mailto:swaroop894@example.com" target="_blank">swaroop894@gmail.com </a>
          <a href="https://github.com/SwaroopAkkineni" target="_blank">Github </a>
          <a href="https://www.linkedin.com/in/swaroop-akkineni" target="_blank">LinkedIn </a>
          <a href="https://twitter.com/AkkineniSwaroop" target="_blank">Twitter </a>
          <a href="../assets/SwaroopAkkineniResume.pdf">Resume</a>
        </div>
      </div>
    </div>
    <div class="rightBar">
      <p >About Me</p>
      <p style="color:red !important;">Originally from New Jersey, I went to school
      at the University of Pittsburgh, where I received a B.S. in Computer Engineering.
      I then worked at UPMC Enterprises on the Clinical Tools team, where I worked with
      Microsoft Research on the EmpowerMD Project and briefly worked on a chatbot. My team
      eventually evolved into a separate startup called Abridge Ai, where I have been currently working at.
      </p>
      <p style="color:red !important;">I have experience working on Vue.js, React-Native, CSS/SCSS, Java, Hapi-Fhir Spring,
        Python, Flask, Node.js, Docker, Kubernetes, Azure, GCP, MySql, and Firebase.
        I'm looking for new opportunities that will challenge me and allow me learn a great deal more about
        software architecture and a scaling services.
      </p>
      <p style="color:red !important;">
        Fun Facts: I'm an avid runner, lifter, and Smash Bros player
      </p>
    </div>
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

<style lang="scss" scoped>
  .main {
    padding: 0;
    margin: 0;
    min-height: 100% !important;
    height: 100%;

    p {
      display: block;
      color: #ffffff !important;
      font-size: 17px;
      line-height: 2em !important;
    }
    a {
      display: block;
      color: #ffffff !important;
      font-size: 17px;
      line-height: 2em !important;
    }

    .bold {
      font-weight: bold;
    }

    .leftBar {
      background-position: left 0px;
      background-color: #4BA3C3;
      width: 15%;
      float: left;
      height: 100%;

      .text{
        margin-left: 5%;
        float: right;
        text-align: left;

        .imageDiv {
          padding-top: 40%;
          padding-right: 10%;

          .resize {
            height: 150px;
            width: 150px;
            border-radius: 50%;
          }
        }

        .intro {
          padding: 20% 0 20% 0;
        }
      }
    }

    .rightBar{
      background-position: left 0px;
      width: 85%;
      float: right;
      height: 100%;
    }
  }
</style>
