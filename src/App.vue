<template>
  <div className="font">
    <MenuBar />
    <Home />
    <About />
    <Skills />
    <WorkExperience />
    <Projects />
    <Contact />
  </div>
</template>

<script>
import MenuBar from './components/MenuBar.vue'
import Home from './components/Home.vue'
import About from './components/About.vue'
import Skills from "@/components/Skills.vue";
import WorkExperience from "@/components/WorkExperience.vue";
import Projects from './components/Projects.vue'
import Contact from './components/Contact.vue'

export default {
  name: 'App',
  components: {
    MenuBar,
    Home,
    About,
    Skills,
    WorkExperience,
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
  background: #2ea44f;
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background: #207237;
}

@media only screen and (max-width: 600px) {
  .font {
    width: 189%;
  }
}
</style>
