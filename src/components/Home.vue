<template>
  <div className="homeContainer">
    <h1>Hey, I'm Thomas Schmid</h1>
    <div>A highly motivated and task-oriented self-starter seeking employment as a software engineer where I can build on my existing skills and grow into a well-rounded frontend developer.</div>
  </div>
</template>
  
  <script>
  export default {
    name: 'Home'
  }
  </script>
  
  
<style scoped>
.homeContainer {
  display: flex;
  flex-direction: column;
  margin: auto;
  width: 100%;
  background-color: blue;
}

.homeContainer h1 {
  margin: 10px auto;
  background-color: orange
}

.homeContainer div {
  width: 50%;
  font-size: 20px;
  margin: 10px auto;
  text-align: center;
  background-color: yellow;
}


</style>