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
      <div>HOME</div>
      <div>ABOUT</div>
      <div>PROJECTS</div>
      <div>CONTACT</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MenuBar'
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
  font-family: "Verdana";
}


.navContainer {
  display: flex;
  flex-direction: row;
  align-items: center;
  margin: 2px 2px 2px auto;
}

.navContainer div {
  margin: 0px 30px;
  font-family: "Verdana";
  font-weight: bold;
  font-size: 15px;
  transition: 0.3s;
}

.navContainer div:hover {
  color: rgb(0, 180, 0);
}

</style>
