<template>
    <div className="contactContainer">
      <div>
        <div> 
          Thomas Schmid
        </div>
        <div> 
          A highly motivated and task-oriented self-starter seeking employment as a software engineer in order to build on my existing skills and grow into a well-rounded frontend developer.
        </div>
      </div>
      <div> 
        Contact Info
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
}

.contactContainer div {
  margin: auto;
  width: 75%;
}

</style>