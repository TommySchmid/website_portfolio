<template>
  <div className="homeContainer" id="home">
    <h1>HEY, I'M THOMAS SCHMID</h1>
    <div>A highly motivated and task-oriented self-starter seeking employment as a software engineer in order to build on my existing skills and grow into a well-rounded frontend developer.</div>
    <button @click="handleProjectsClick" class="button-3" role="button">PROJECTS</button>
  </div>
</template>
  
  <script>
  export default {
    name: 'Home',
    methods: {
      handleProjectsClick: function() {
        document.getElementById('projects').scrollIntoView();
      }
    }
  }
  </script>
  
  
<style scoped>
.homeContainer {
  display: flex;
  flex-direction: column;
  margin: auto;
  width: 100%;
}

.homeContainer h1 {
  margin: 245px auto 20px;
  font-size: 45px;
  color: rgb(17, 17, 17)
}

.homeContainer div {
  width: 65%;
  line-height: 1.7;
  font-size: 20px;
  margin: 25px auto 35px;
  text-align: left;
  color: rgb(17, 17, 17)
}

.button-3 {
  width: 35%;
  height: 55px;
  margin: 45px auto 325px;

  appearance: none;
  background-color: #2ea44f;
  border: 1px solid rgba(27, 31, 35, .15);
  border-radius: 6px;
  box-shadow: rgba(27, 31, 35, .1) 0 1px 0;
  box-sizing: border-box;
  color: #fff;
  cursor: pointer;
  display: inline-block;
  font-family: -apple-system,system-ui,"Segoe UI",Helvetica,Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji";
  font-size: 14px;
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

.button-3:focus:not(:focus-visible):not(.focus-visible) {
  box-shadow: none;
  outline: none;
}

.button-3:hover {
  background-color: #2c974b;
}

.button-3:focus {
  box-shadow: rgba(46, 164, 79, .4) 0 0 0 3px;
  outline: none;
}

.button-3:disabled {
  background-color: #94d3a2;
  border-color: rgba(27, 31, 35, .1);
  color: rgba(255, 255, 255, .8);
  cursor: default;
}

.button-3:active {
  background-color: #298e46;
  box-shadow: rgba(20, 70, 32, .2) 0 1px 0 inset;
}

</style>