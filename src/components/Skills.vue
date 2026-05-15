<template>
  <div class="skillsContainer" id="skills">
    <h2>Skills</h2>
    <div class="skillsGrid">
      <div class="skillsCategory">
        <h3>Programming Languages</h3>
        <div class="skillsListContainer">
          <div>Java</div>
          <div>Kotlin</div>
          <div>JavaScript</div>
          <div>PHP</div>
          <div>HTML</div>
          <div>CSS</div>
        </div>
      </div>

      <div class="skillsCategory">
        <h3>Frameworks & Libraries</h3>
        <div class="skillsListContainer">
          <div>React</div>
          <div>Redux</div>
          <div>Vue</div>
          <div>Vuex</div>
          <div>Rhino</div>
          <div>Axios</div>
          <div>Cypress</div>
        </div>
      </div>

      <div class="skillsCategory">
        <h3>Cloud & DevOps</h3>
        <div class="skillsListContainer">
          <div>AWS</div>
          <div>Kubernetes</div>
          <div>Docker</div>
          <div>Terraform</div>
          <div>REST APIs</div>
          <div>Firebase</div>
          <div>Bitrise</div>
          <div>Testkube</div>
        </div>
      </div>

      <div class="skillsCategory">
        <h3>Engineering Practices</h3>
        <div class="skillsListContainer">
          <div>System Design</div>
          <div>Automation Frameworks</div>
          <div>CI/CD</div>
          <div>Developer Tooling</div>
          <div>Agile Scrum</div>
          <div>Testing Infrastructure</div>
          <div>Platform Reliability</div>
        </div>
      </div>

      <div class="skillsCategory">
        <h3>Development Tools</h3>
        <div class="skillsListContainer">
          <div>Claude Code</div>
          <div>Codex</div>
          <div>Git</div>
          <div>GitHub</div>
          <div>IntelliJ</div>
          <div>Gradle</div>
          <div>Swagger</div>
          <div>Postman</div>
          <div>Datadog</div>
          <div>LaunchDarkly</div>
          <div>Charles Proxy</div>
          <div>Proxyman</div>
          <div>Jira</div>
          <div>Confluence</div>
          <div>Surge</div>
        </div>
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'Skills',
}
</script>

<style scoped>
.skillsContainer {
  margin: 0px 3%;
  justify-items: center;
}

.skillsContainer h2 {
  margin: 5px;
  text-align: left;
  font-size: 35px;
}

/* 2-column layout for categories */
.skillsGrid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 30px;
  align-items: start;
}

.skillsCategory {
  margin-bottom: 10px;
}

.skillsCategory h3 {
  margin: 10px;
  text-align: left;
  font-size: 24px;
}

/* skill pills */
.skillsListContainer {
  margin: auto;
  display: flex;
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

/* mobile */
@media only screen and (max-width: 600px) {

  .skillsGrid {
    grid-template-columns: 1fr;
  }

  .skillsCategory h3 {
    text-align: center;
  }

  .skillsListContainer {
    justify-content: center;
  }
}
</style>