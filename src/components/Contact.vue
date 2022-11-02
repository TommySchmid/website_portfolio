<template>
    <div className="contactContainer" id="contact">
      <div>
        <div> 
          Thomas Schmid
        </div>
        <div> 
          A highly motivated and task-oriented self-starter seeking employment as a software engineer in order to build on my existing skills and grow into a well-rounded frontend developer.
        </div>
      </div>
      <div className="contactInfo">
        <div><a href="https://github.com/TommySchmid">Github</a></div>
        <div><a href="https://www.linkedin.com/in/thomas-schmid-a89729b2/">LinkedIn</a></div>
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