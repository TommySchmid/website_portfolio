<template>
  <div className="aboutContainer" id="about">
    <h1>ABOUT ME</h1>
    <h4>Here you will find more information on how I have come up to proficiency, and the technologies I have studied and worked with.</h4>
    <div className="aboutSubContainer">
      <div className="GTNMContainer">
        <div className="info">
          <h2>Get to know me!</h2>
          <div>
            I am a self taught Frontend Software Engineer looking to take my development skills to the next level.
          </div>
          <div>
            After making the decision to pursue a career in software development and investing my time, I now have example work to showcase, open source development experience, and 5+ years of experience serving on engineering teams in varying capacities.
          </div>
          <div> 
            I am open to job opportunities through which I can continue to grow and learn individually and as a teammate, and contribute to a greater cause.
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
  scroll-behavior: smooth;
}

.aboutContainer h1 {
  margin: 0px auto 25px;
}

.aboutContainer h4 {
  margin: 0px auto 65px;
  width: 50%;
  line-height: 1.7;
  text-align: left;
  color: rgb(17, 17, 17)
}

.aboutSubContainer {
  display: flex;
  flex-direction: row;
  margin: 20px auto 245px;
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

.info div {
  margin: 10px;
  line-height: 1.7;
}

.skillsContainer {
  margin: 0px 3%;
  width: 50%;
}

.skillsContainer h2 {
  margin: 5px;
  text-align: left;
}

.skillsListContainer {
  margin: auto;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
}

.skillsListContainer div {
  color: white;
  margin: 10px;
  border-radius: 25px;
  background: #2ea44f;
  padding: 20px;
}

</style>