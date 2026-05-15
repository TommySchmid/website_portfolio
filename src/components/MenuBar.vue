<template>
  <div className="menuContainer">
    <div className="pictureContainer">
      <div className="picture">
        <img src="../assets/tschmid.jpg" style="width:75px;height:75px;" />
      </div>
      <div className="name">
        Thomas Schmid
      </div>
    </div>
    <div className="navContainer">
      <div @click="scrollToTop">HOME</div>
      <div @click="scrollToSection('about')">ABOUT</div>
      <div @click="scrollToSection('workExperience')">WORK EXPERIENCE</div>
      <div @click="scrollToSection('projects')">PROJECTS</div>
      <div @click="scrollToBottom">CONTACT</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MenuBar',
  methods: {
    scrollToTop() {
      window.scrollTo({ top: 0, behavior: 'smooth' })
    },

    scrollToBottom() {
      window.scrollTo({
        top: document.documentElement.scrollHeight,
        behavior: 'smooth'
      })
    },

    scrollToSection(id) {
      document.getElementById(id)?.scrollIntoView({
        behavior: 'smooth',
        block: 'start'
      })
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
  transition: all 0.5s ease;
}

.picture:hover {
  transform: scale(4);
  margin-top: 110px;
  margin-left: 105px;
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
