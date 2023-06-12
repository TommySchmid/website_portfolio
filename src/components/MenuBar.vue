<template>
  <div className="menuContainer">
    <div className="pictureContainer">
      <div>
        <img src="../assets/tschmid.jpg" style="width:75px;height75px;" />
      </div>
      <div>
        Thomas Schmid
      </div>
    </div>
    <div className="navContainer">
      <div @click="handleHomeClick">HOME</div>
      <div @click="handleAboutClick">ABOUT</div>
      <div @click="handleProjectsClick">PROJECTS</div>
      <div @click="handleContactClick">CONTACT</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MenuBar',
  methods: {
    handleHomeClick: function() {
      document.getElementById('home').scrollIntoView({block: "start"});
    },
    handleAboutClick: function () {
      document.getElementById('about').scrollIntoView({block: "end"});
    },
    handleProjectsClick: function () {
      document.getElementById('projects').scrollIntoView({block: "start"});
    },
    handleContactClick: function () {
      document.getElementById('contact').scrollIntoView({block: "end"});
    }
  }
}
</script>

<style scoped>

img {
  border-radius: 50%;
}

.menuContainer {
  display: flex;
  flex-direction: row;
  position: sticky;
  top:0;
  width: 100%;
  background-color: white;
}

.pictureContainer {
  display: flex;
  flex-direction: row;
  align-items: center;
  margin: 2px;
}

.pictureContainer div {
  margin: 5px;
}

.navContainer {
  display: flex;
  flex-direction: row;
  align-items: center;
  margin: 2px 2px 2px auto;
}

.navContainer div {
  margin: 0px 30px;
  font-weight: bold;
  font-size: 15px;
  transition: 0.3s;
}

.navContainer div:hover {
  color: #2ea44f;
  cursor: pointer;
}

</style>
