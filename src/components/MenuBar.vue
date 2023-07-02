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
      window.scrollTo({top: 0, behavior: 'smooth'});
    },
    handleAboutClick: function () {
      window.scrollTo({top: 550, behavior: 'smooth'})
    },
    handleProjectsClick: function () {
      window.scrollTo({top: 950, behavior: 'smooth'})
    },
    handleContactClick: function () {
      window.scrollTo({top: document.body.scrollHeight, behavior: 'smooth'})
    }
  }
}
</script>

<style scoped>

img {
  border-radius: 50%;
}

/* z-index set in About.vue to accommodate skills hover enlarging */

.menuContainer {
  display: flex;
  flex-direction: row;
  position: sticky;
  top:0;
  width: 100%;
  background-color: white;
  z-index: 3;
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
