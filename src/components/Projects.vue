<template>
    <div className="projectsContainer">
      <h1>PROJECTS</h1>
      <h4>Here you will find links to various projects, including three iterations of the Crate Companion web application.</h4>
      <div className="projectsSubContainer"> 
        <a href="https://github.com/cuttle-cards/cuttle" target="_blank">Cuttle.cards</a> - Open source
        <div>
          Core team at cuttle.cards. <a href="https://github.com/cuttle-cards/cuttle/commits?author=TommySchmid" target="_blank">Contributions</a> enhance Cypress test suite, add logical javascript operators to Vue framework dictating style application and game state, fix application breaking bugs, and refactor existing code.
        </div>
        <a href="https://github.com/TommySchmid/vue_music_viewer" target="_blank">Crate Companion v2</a>
        <div>Crate Companion is the final iteration of a music inspired web application that I created. It combines the concepts of having music at your fingertips, and sharing music with others, into one. This version was created using Vue.</div>
        <a href="https://crate-companion.surge.sh/">Crate Companion v1</a>
        <div>An earlier version of Crate Companion using React to display band information based on user input.</div>
        <a href="https://codepen.io/TommySchmid4954">Miscellaneous Apps</a>
        <div>A series of miscellaneous applications written on Codepen using React. Applications range from a drum machine to a calculator.</div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Projects'
  }
  </script>
  
  
<style scoped>
.projectsContainer {
  display: flex;
  flex-direction: column;
  margin: 0px auto 150px;
}

.projectsContainer h1 {
  margin: 0px auto 25px;
}

.projectsContainer h4 {
  width: 50%;
  text-align: center;
  margin: 0px auto 45px;
  color: rgb(17, 17, 17);
  line-height: 1.7;
}

.projectsSubContainer {
  margin: auto;
  width: 75%;
}

.projectsSubContainer div {
  text-align: left;
  margin: 5px;
  border-radius: 25px;
  border: 2px solid #2ea44f;
  padding: 20px;
  font-size: 12px;
}

a {
  color: #2ea44f
}

</style>