<template>
  <div className="aboutContainer">
    <h1>About Me</h1>
    <h3>Here you will find more information on how I have come up to proficiency, and the technologies I have studied and worked with.</h3>
    <div className="aboutSubContainer">
      <div className="GTNMContainer">
        <h2>Get to know me!</h2>
        <div className="info">
          <div>
            I am a self taught Frontend Web Developer looking to take my development skills to the next level.
          </div>
          <div>
            After making the decision to pursue a career in software development and investing my time, I now have example work to showcase, open source development experience, and 5+ years of experience serving on engineering teams in varying capacities.
          </div>
        </div>
      </div>
      <div className="skillsContainer">
        <h2>Skills</h2>
        <div className="skillsListContainer">
          <div>Skill</div>
          <div>Skill</div>
          <div>Skill</div>
          <div>Skill</div>
          <div>Skill</div>
          <div>Skill</div>
          <div>Skill</div>
          <div>Skill</div>
          <div>Skill</div>
          <div>Skill</div>
          <div>Skill</div>
          <div>Skill</div>
          <div>Skill</div>
          <div>Skill</div>
          <div>Skill</div>
          <div>Skill</div>
          <div>Skill</div>
          <div>Skill</div>
          <div>Skill</div>
          <div>Skill</div>
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
  background-color: red;
}

.aboutContainer h1 {
  margin: auto;
}

.aboutContainer h3 {
  margin: auto;
}

.aboutSubContainer {
  display: flex;
  flex-direction: row;
  background-color: pink;
  margin: 2px;
}

.GTNMContainer {
  margin: auto;
  width: 50%;
  text-align: left;
  background-color: green;
}

.GTNMContainer h2 {
  margin: 5px;
  text-align: center;
}

.info {
  text-align: left;
  width: 50%;
  margin: auto;
}

.skillsContainer {
  margin: auto;
  width: 50%;
  background-color: orange;
  margin: 2px;
}

.skillsContainer h2 {
  text-align: center;
}

.skillsListContainer {
  margin: auto;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  width: 50%;
}

.skillsListContainer div {
  margin: 10px;
}

</style>