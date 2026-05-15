<template>
  <div className="aboutContainer" id="about">
    <div className="aboutSubContainer">
      <div className="GTNMContainer">
        <div className="info">
          <h2>Get to know me!</h2>
          <div>
            I'm a software engineer with experience building resilient systems, internal tooling, automation frameworks, and scalable developer workflows.
          </div>
          <div>
            Starting as a customer service representative with an interest in frontend development, I challenged myself to transition into engineering — first as a Manual QA Engineer at URBN, and later as a Senior SDET at Fanatics Betting and Gaming.
          </div>
          <div>
            In my most recent role, I designed resilient testing systems, improved developer workflows, built internal tooling, and helped engineering teams ship software with greater confidence and reliability.
          </div>
          <div>
            I’m currently looking for opportunities where I can contribute across the full software development lifecycle while continuing to grow as a full-stack engineer.
          </div>
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
#about {
  scroll-margin-top: 90px; /* match your menu bar height */
}

.aboutContainer {
  display: flex;
  flex-direction: column;
  margin: auto;
  width: 100%;
}

.aboutContainer h1 {
  margin: 0px auto 25px;
  font-size: 50px;
}

.aboutDescription {
  margin: 0px auto 15px;
  font-size: 25px;
  width: 55%;
  line-height: 1.7;
  text-align: center;
  color: rgb(17, 17, 17);
  background-color: rgb(211, 253, 211);
  border-radius: 25px;
  padding: 20px;
}

.aboutSubContainer {
  display: flex;
  flex-direction: row;
  margin: 20px auto 50px;
}

.GTNMContainer {
  margin: 0px 3%;
  width: 100%;
}

.GTNMContainer h2 {
  margin: 5px;
  text-align: left;
}

.info {
  justify-items: center;
}

.info h2 {
  font-size: 35px;
}

.info div {
  margin: 20px;
  line-height: 1.7;
  font-size: 20px;
  transition: all 0.5s ease;
  width: 90%;
}

.info div:hover{
  background-color: rgb(211, 253, 211);
  border-radius: 25px;
  padding: 10px;
  margin: -0.5px;
}

@media only screen and (max-width: 600px) {
  .aboutContainer h4{
    width: 75%;
  }

  .info div{
    width: 100%;
  }
}

</style>