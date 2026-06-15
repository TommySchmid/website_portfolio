<template>
    <div className="contactContainer" id="contact">
      <div>
        <div> 
          Thomas Schmid
        </div>
        <div> 
          A highly motivated and task-oriented self-starter seeking continued upward career trajectory through backend, fullstack, and devops positions.
        </div>
      </div>
      <div className="contactInfo">
        <div><a href="https://github.com/TommySchmid" target="_blank">Github</a></div>
        <div><a href="https://www.linkedin.com/in/thomas-schmid-phl/" target="_blank">LinkedIn</a></div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Contact'
  }
  </script>
  
  
<style scoped>
.contactContainer {
  display: flex;
  flex-direction: row;
  width: 100%;
  color: white;
  background-color: rgb(17, 17, 17);
}

.contactContainer div {
  margin: 15px;
  width: 85%;
}

.contactInfo {
  display: flex;
  flex-direction: column;
  text-align: right;
}

a {
  color: #2ea44f;
}

</style>