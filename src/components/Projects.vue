<template>
    <div className="projectsContainer">
      <h1>Projects</h1>
      <h3>Here you will find links to various projects, including three iterations of the Crate Companion web application.</h3>
      <div className="projectsSubContainer"> 
        <div>Project 1</div>
        <div>Project 2</div>
        <div>Project 3</div>
        <div>Project 4</div>
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
}

.projectsContainer h1 {
  margin: auto;
}

.projectsContainer h3 {
  margin: auto;
}

.projectsSubContainer {
  margin: auto;
  width: 45%;
}

.projectsSubContainer div {
  text-align: center;
  margin: 5px;
  box-shadow: rgba(50, 50, 93, 0.25) 0px 50px 100px -20px, rgba(0, 0, 0, 0.3) 0px 30px 60px -30px, rgba(10, 37, 64, 0.35) 0px -2px 6px 0px inset;
  width: 100%
}

</style>