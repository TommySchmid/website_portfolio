<template>
  <div className="aboutContainer" id="about">
    <div className="aboutSubContainer">
      <div className="GTNMContainer">
        <div className="info">
          <h2>Get to know me!</h2>
          <div>
            I am a self taught Frontend Software Engineer looking to take my development skills to the next level.
          </div>
          <div>
            After making the decision to pursue a career in software development and investing my time, I have example work to showcase, open source development experience, and 5+ years of experience serving on engineering teams in varying capacities.
          </div>
          <div> 
            I am open to job opportunities through which I can continue to grow and learn individually and as a teammate.
          </div>
        </div>
      </div>
      <div className="skillsContainer">
        <h2>Skills</h2>
        <div className="skillsListContainer">
          <div>Vue/Vuex</div>
          <div>React/Redux</div>
          <div>JavaScript</div>
          <div>HTML</div>
          <div>CSS</div>
          <div>Cypress</div>
          <div>Git</div>
          <div>Jira/Confluence</div>
          <div>Axios</div>
          <div>Firebase</div>
          <div>Surge</div>
          <div>Charles/Proxyman</div>
          <div>Agile Scrum</div>
        </div>
      </div>
    </div>
  </div>
</template>
  
  <script>
  export default {
    name: 'About',
  }
  </script>
  
<style scoped>
.aboutContainer {
  display: flex;
  flex-direction: column;
  margin: auto;
  width: 100%;
}

.aboutContainer h1 {
  margin: 0px auto 25px;
  font-size: 50px;
}

.aboutDescription {
  margin: 0px auto 15px;
  font-size: 25px;
  width: 55%;
  line-height: 1.7;
  text-align: center;
  color: rgb(17, 17, 17);
  background-color: rgb(211, 253, 211);
  border-radius: 25px;
  padding: 20px;
}

.aboutSubContainer {
  display: flex;
  flex-direction: row;
  margin: 20px auto 50px;
}

.GTNMContainer {
  margin: 0px 3%;
  width: 50%;
}

.GTNMContainer h2 {
  margin: 5px;
  text-align: left;
}

.info {
  text-align: left;
  margin: auto;
}

.info h2 {
  font-size: 35px;
}

.info div {
  margin: 10px;
  line-height: 1.7;
  font-size: 20px;
  transition: all 0.5s ease;
}

.info div:hover{
  background-color: rgb(211, 253, 211);
  border-radius: 25px;
  padding: 10px;
  margin: -0.5px;
}

.skillsContainer {
  margin: 0px 3%;
  width: 50%;
}

.skillsContainer h2 {
  margin: 5px;
  text-align: left;
  font-size: 35px;
}

/* z-index set in MenuBar.vue to accommodate skills hover enlarging */
.skillsListContainer {
  margin: auto;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  z-index: 1;
}

.skillsListContainer div {
  color: white;
  margin: 10px;
  border-radius: 25px;
  background: #2ea44f;
  padding: 20px;
  font-size: 20px;
  box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
  transition: all 0.5s ease;
  z-index: 2;
}

.skillsListContainer div:hover {
   transform: scale(1.1);
}

@media only screen and (max-width: 600px) {
  .aboutContainer h4{
    width: 75%;
  }

  .aboutDescription{
    width: 75%;
  }

  .aboutSubContainer{
    display: flex;
    flex-direction: column;
    margin: 50px auto 50px;
    align-items: center;
  }

  .GTNMContainer {
    width: 75%;
    margin-bottom: 25px;
  }
  
  .info div{
    width: 100%;
  }

  .skillsContainer{
    width: 75%;
  }
}

</style>