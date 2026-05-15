<template>
  <div className="homeContainer" id="home">
    <h1>HEY, I'M THOMAS SCHMID</h1>
    <div>I’m a software engineer who enjoys building systems that make products more reliable and teams more effective.
    <br><br>
      From SDK development to automation frameworks, tooling, and distributed systems design, I’ve spent my career creating solutions that scale while improving the developer experience behind the scenes.</div>
  </div>
</template>
  
  <script>
  export default {
    name: 'Home',
    methods: {
      handleProjectsClick: function() {
        window.scrollTo({top: 950, behavior: 'smooth'})
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
  text-align: center;
}

.homeContainer h1 {
  display: flex;
  flex-direction: column;
  margin: 15px auto 20px;
  font-size: 65px;
  color: rgb(17, 17, 17);
}

.homeContainer div {
  width: 75%;
  line-height: 1.7;
  font-size: 35px;
  margin: 15px auto 15px;
  text-align: center;
  color: rgb(17, 17, 17);
  background-color: rgb(211, 253, 211);
  border-radius: 25px;
  padding: 20px;
}

.button-3 {
  min-width: 15%;
  height: 55px;
  margin: 15px auto 100px;

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
  font-size: 24px;
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

.button-3:hover {
  background-color: #2c974b;
}

@media only screen and (max-width: 600px){
  .button-3{
    width: 25%;
  }
}

</style>