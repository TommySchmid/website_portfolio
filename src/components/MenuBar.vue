<template>
  <div className="menuContainer">
    <div className="pictureContainer">
      Thomas Schmid
    </div>
    <div className="navContainer">
      <div>Home</div>
      <div>About</div>
      <div>Projects</div>
      <div>Contact</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MenuBar'
}
</script>


<style scoped>

.menuContainer {
  display: flex;
  flex-direction: row;
  background-color: green;
}

.pictureContainer{
  margin: 2px;
  background-color: pink;
}

.navContainer {
  display: flex;
  flex-direction: row;
  margin: 2px 2px 2px auto;
  background-color: blueviolet;
}

.navContainer div {
  margin: 0px 30px;
}

</style>
