<template>
    <div className="projectsContainer" id="projects">
      <h1>PROJECTS</h1>
      <div className="projectsDescription"> 
        Here you will find links to various projects that I have contributed to and created, and a bit of the inspiration and information behind each of them.
      </div>
      <div> 
        <div id="projectHeader">inStryde</div>
        <div className="projectsSubContainer">
          Since beginning an ongoing internship with <a href="https://www.instryde.com/" target="_blank">inStryde</a>, a North Carolina startup and TechStars grad, I have led the development and creation of the in-house application used for processing and filling customer orders. I was relied on for architectural and functional decision making. This project was initially created relying heavily on the material-ui library. My refactor work was a complete rebuild using custom code. Features include grid checkbox functionality for uploading and deleting customer entries, column toggles for viewing preference, enhancing application data update and retrevial from Firebase, and a reactive search-as-you-type search function that updates displayed information in real time. 
          <div className="imageContainer">
            <img src="../assets/instryde.png" />
          </div>
        </div>
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
        <div id="projectHeader">Crate Companion</div>
        <div className="projectsSubContainer">
          Crate Companion is a web application used to quickly identify a band's most popular albums and tracks. While digging through my local Philadelphia record stores, I use this site to help determine which records i'd like to add to my collection. React is used as the frontend framework with Axios making network requests. The rest is JSX and CSS. Visually optimized for desktop and mobile viewing.
          <div id="buttonAlign">
            <button class="button-3" onclick="window.open('https://github.com/TommySchmid/crate_companion')">View on Git</button>
            <button class="button-3" onclick="window.open('https://cratecompanion.surge.sh/')">View Site</button>
          </div>
          <div className="imageContainer">
            <img src="../assets/cc.png" />
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
  width: 55%;
  font-size: 25px;
  text-align: center;
  margin: 0px auto 45px;
  color: rgb(17, 17, 17);
  line-height: 1.7;
  background-color: rgb(211, 253, 211);
  border-radius: 25px;
  padding: 20px;
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
  border-radius: 25px;
  width: fit-content;
  text-align: center;
  margin-top: 50px;
  margin-left: 12%;
  margin-bottom: 5px;
  padding: 10px;
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