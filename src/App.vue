<template>
  <div id="app">
    <Hero />
    <AboutMe />
    <Contact />
  </div>
</template>

<script>
import Hero from './components/Hero.vue'
import AboutMe from './components/AboutMe.vue'
import Contact from './components/Contact.vue'

export default {
  name: 'App',
  components: {
    Hero, AboutMe, Contact
  }
}
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600");

* {
  box-sizing: border-box;
}
body {
  font-family: Montserrat, sans-serif;
  margin: 0;
  padding: 0;
}
</style>
