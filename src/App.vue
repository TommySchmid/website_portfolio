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
.font {
  font-family: "Verdana";
}
</style>
