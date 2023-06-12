<template>
  <div className="font">
    <MenuBar />
    <Home />
    <About />
    <Projects />
    <Contact />
  </div>
</template>

<script>
import MenuBar from './components/MenuBar.vue'
import Home from './components/Home.vue'
import About from './components/About.vue'
import Projects from './components/Projects.vue'
import Contact from './components/Contact.vue'

export default {
  name: 'App',
  components: {
    MenuBar,
    Home,
    About,
    Projects,
    Contact
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Lato');

.font {
  font-family: "Lato";
  cursor: default;
}

/* width */
::-webkit-scrollbar {
  width: 10px;
}

/* Track */
::-webkit-scrollbar-track {
  background: #f1f1f1;
}

/* Handle */
::-webkit-scrollbar-thumb {
  background: rgb(211, 253, 211);
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background: #2ea44f;
}

@media only screen and (max-width: 600px) {
  .font {
    width: 189%;
  }
}
</style>
