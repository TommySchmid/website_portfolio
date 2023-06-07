<template>
    <div className="projectsContainer" id="projects">
      <h1>PROJECTS</h1>
      <div className="projectsDescription"> 
        Here you will find links to various projects that I have contributed to and created, and a bit of the inspiration and information behind each of them.
      </div>
      <div> 
        <div id="projectHeader">Cuttle.cards</div>
        <div className="projectsSubContainer">
          Core team at cuttle.cards. <a href="https://github.com/cuttle-cards/cuttle/commits?author=TommySchmid" target="_blank">Contributions</a> enhance Cypress test suite, add logical javascript operators to Vue framework dictating style application and game state, fix application breaking bugs, and refactor existing code. The open source Cuttle community has given me the opportunity to contribute to a large web application in a collaborative and remote setting. The technologies used include Vue as the frontend framework, Cypress as the testing suite, and Sails.js as the backend server.
          <div id="buttonAlign">
            <button class="button-3" onclick="window.open('https://github.com/cuttle-cards/cuttle')">View on Git</button>
          </div>
          <div className="imageContainer">
            <img src="../assets/cuttle.png" />
          </div>
        </div>
        <div id="projectHeader">Crate Companion v2</div>
        <div className="projectsSubContainer">
          Crate Companion is the final iteration of a music inspired web application that I created. It combines the concepts of having music at your fingertips, and sharing music with others, into one. Building off of v1, I created v2 as a way to practice working with multi-page applications, combining Crate Companion v1 and the Ultimate Music List. The technologies used include Vue and Vuex as the frontend framework and state managment, Firebase Authentication to manage login state, Axios to handle network requests, and Vue Router to ensure smooth client side routing.
          <div id="buttonAlign">
            <button class="button-3" onclick="window.open('https://github.com/TommySchmid/vue_music_viewer')">View on Git</button>
          </div>
          <div className="imageContainer">
            <img src="../assets/v2.png" />
          </div>
        </div>
        <div id="projectHeader">Crate Companion v1</div>
        <div className="projectsSubContainer">
          An earlier version of Crate Companion using React to display band information based on user input. I created this as a way to quickly pull up a band's top albums and songs, and a way to practice creating single page applications. The technologies used include React as the frontend framework and Axios to handle network requests.
          <div id="buttonAlign">
            <button class="button-3" onclick="window.open('https://github.com/TommySchmid/music_viewer')">View on Git</button>
          </div>
          <div className="imageContainer">
            <img src="../assets/v1.png" />
          </div>
        </div>
        <div id="projectHeader">Ultimate Music List</div>
        <div className="projectsSubContainer">
          The Ultimate Music List was one of my first project ideas. This application was created to serve as an easy way to share music with family and friends. React is used as the frontend framework, Axios is used to handle network requests, storing and retrieving dispalyed information from a Firebase database.
          <div id="buttonAlign">
            <button class="button-3" onclick="window.open('https://github.com/TommySchmid/Ultimate-Music-List')">View on Git</button>
          </div>
          <div className="imageContainer">
            <img src="../assets/uml.png" />
          </div>
        </div>
        <div id="projectHeader">Miscellaneous Apps</div>
        <div className="projectsSubContainer">
          A series of miscellaneous applications written on Codepen using React. Applications range from a drum machine to a calculator.
          <div id="buttonAlign">
            <button class="button-3" onclick="window.open('https://codepen.io/TommySchmid4954')">View on CodePen</button>
          </div>
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
  font-size: 50px;
}

.projectsDescription {
  width: 50%;
  font-size: 25px;
  text-align: center;
  margin: 0px auto 45px;
  color: rgb(17, 17, 17);
  line-height: 1.7;
  background-color: rgb(211, 253, 211);
  border-radius: 25px;
}

.projectsSubContainer {
  margin: auto;
  width: 75%;
  border-radius: 25px;
  color: rgb(17, 17, 17);
  border: 2px solid #2ea44f;
  background-color: rgb(244, 255, 244);
  padding: 20px;
  font-size: 20px;
  line-height: 1.7;
}

.projectsSubContainer div {
  margin: 5px;
}

a {
  color: #2ea44f;
}

.imageContainer {
  text-align: center;
}

.imageContainer img{
  width: 100%
}

img{
  box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
}

#projectHeader {
  display: block;
  font-size: 35px;
  color: #2ea44f;
  background-color: rgb(211, 253, 211);
  border-radius: 15px;
  width: fit-content;
  text-align: center;
  margin-top: 50px;
  margin-left: 12%;
  margin-bottom: 5px;
}

/* Button CSS */

.button-3 {
  min-width: 15%;
  height: 55px;
  margin: 15px 15px;

  appearance: none;
  border: 1px solid rgba(27, 31, 35, .15);
  border-radius: 6px;
  box-shadow: rgba(27, 31, 35, .1) 0 1px 0;
  box-sizing: border-box;
  background-color: #2ea44f;
  cursor: pointer;
  display: inline-block;
  font-family: -apple-system,system-ui,"Segoe UI",Helvetica,Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji";
  font-size: 24px;
  font-weight: 600;
  line-height: 20px;
  padding: 6px 16px;
  text-align: center;
  text-decoration: none;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  vertical-align: middle;
  white-space: nowrap;
  transition: 0.3s;
}

#buttonAlign {
  display: flex;
  flex-direction: row;
  justify-content: center;
}

.button-3:hover {
  background-color: #298e46;
}

.button-3 {
  text-decoration: none;
  color: #fff;
}

@media only screen and (max-width: 600px) {
  .projectsDescription{
    width: 75%;
  }
}

</style>