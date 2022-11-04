<template>
    <div className="projectsContainer" id="projects">
      <h1>PROJECTS</h1>
      <h4>Here you will find links to various projects that I have contributed to and created, and a bit of the inspiration and information behind each of them.</h4>
      <div className="projectsSubContainer"> 
        <a href="https://github.com/cuttle-cards/cuttle" target="_blank" id="projectHeader">Cuttle.cards</a> - Open source
        <div>
          Core team at cuttle.cards. <a href="https://github.com/cuttle-cards/cuttle/commits?author=TommySchmid" target="_blank">Contributions</a> enhance Cypress test suite, add logical javascript operators to Vue framework dictating style application and game state, fix application breaking bugs, and refactor existing code. The open source Cuttle community has given me the opportunity to contribute to a large web application in a collaborative and remote setting. The technologies used include Vue as the frontend framework, Cypress as the testing suite, and Sails.js as the backend server.
          <div className="imageContainer">
            <img src="../assets/cuttle.png" style="width:50%;" />
          </div>
        </div>
        <a href="https://github.com/TommySchmid/vue_music_viewer" target="_blank" id="projectHeader">Crate Companion v2</a>
        <div>
          Crate Companion is the final iteration of a music inspired web application that I created. It combines the concepts of having music at your fingertips, and sharing music with others, into one. Building off of v1, I created v2 as a way to practice working with multi-page applications, combining Crate Companion v1 and the Ultimate Music List. The technologies used include Vue and Vuex as the frontend framework and state managment, Firebase Authentication to manage login state, Axios to handle network requests, and Vue Router to ensure smooth client side routing.
          <div className="imageContainer">
            <img src="../assets/v2.png" style="width:50%;" />
          </div>
        </div>
        <a href="https://github.com/TommySchmid/music_viewer" target="_blank" id="projectHeader">Crate Companion v1</a>
        <div>
          An earlier version of Crate Companion using React to display band information based on user input. I created this as a way to quickly pull up a band's top albums and songs, and a way to practice creating single page applications. The technologies used include React as the frontend framework and Axios to handle network requests.
          <div className="imageContainer">
            <img src="../assets/v1.png" style="width:50%;" />
          </div>
        </div>
        <a href="https://github.com/TommySchmid/Ultimate-Music-List" target="_blank" id="projectHeader">Ultimate Music List</a>
        <div>
          The Ultimate Music List was one of my first project ideas. This application was created to serve as an easy way to share music with family and friends. React is used as the frontend framework, Axios is used to handle network requests, storing and retrieving dispalyed information from a Firebase database.
          <div className="imageContainer">
            <img src="../assets/uml.png" style="width:50%;" />
          </div>
        </div>
        <a href="https://codepen.io/TommySchmid4954" target="_blank" id="projectHeader">Miscellaneous Apps</a>
        <div>
          A series of miscellaneous applications written on Codepen using React. Applications range from a drum machine to a calculator.
        </div>
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
  text-align: left;
  margin: 0px auto 45px;
  color: rgb(17, 17, 17);
  line-height: 1.7;
}

.projectsSubContainer {
  margin: auto;
  width: 75%;
}

.projectsSubContainer div {
  margin: 5px;
  border-radius: 25px;
  color: rgb(17, 17, 17);
  border: 2px solid #2ea44f;
  padding: 20px;
  font-size: 12px;
  line-height: 1.7;
}

a {
  color: #2ea44f;
  text-decoration: none;
}

.imageContainer {
  text-align: center;
}

#projectHeader {
  font-size: 24px;
  background-color: rgb(211, 253, 211);
  border-radius: 25px;
}

</style>