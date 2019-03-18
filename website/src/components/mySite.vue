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
      <div class="body">
        <h2>About Me</h2>
        <p>Originally from New Jersey, I went to school
        at the University of Pittsburgh, where I received a B.S. in Computer Engineering.
        I then worked at UPMC Enterprises on the Clinical Tools team, where I worked with
        Microsoft Research on the EmpowerMD Project and briefly worked on a chatbot. My team
        eventually evolved into a separate startup called Abridge Ai, where I have been currently working at.
        </p>
        <p>I have experience working on Vue.js, React-Native, CSS/SCSS, Java, Hapi-Fhir Spring,
          Python, Flask, Node.js, Docker, Kubernetes, Azure, GCP, MySql, and Firebase.
          I'm looking for new opportunities that will challenge me and allow me learn a great deal more about
          software architecture and a scaling services.
        </p>
        <p>
          <p class="bold inline">Fun Facts: </p>
          <p class="inline">I'm an avid runner, lifter, and Smash Bros player</p>
        </p>
      </div>
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
    margin: 0;
    min-height: 100% !important;
    height: 100%;

    .bold {
      font-weight: bold;
    }

    .inline {
      display: inline;
    }

    .leftBar {
      padding: 5% 0 0 0;
      background-position: left 0px;
      background-color: #230903;
      width: 15%;
      float: left;
      height: 100%;

      a, p {
        display: block;
        color: #ffffff !important;
        font-size: 17px;
        line-height: 2em !important;
      }

      .text{
        margin-left: 5%;
        float: right;
        text-align: left;

        .imageDiv {
         text-align: center;
         margin-left: -5% !important;

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
      padding: 5% 0 0 0;
      background-position: left 0px;
      background-color: #fffffff;
      color:  #230903;
      width: 85%;
      height: 100%;
      float: right;

      .body {
        margin: 0 10% 0 10%;
      }
    }
  }
</style>
