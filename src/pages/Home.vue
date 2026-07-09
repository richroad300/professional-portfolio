<script setup>
import Hero from '../components/Hero.vue'
import About from '../components/About.vue'
import Career from '../components/Career.vue'
import Projects from '../components/Projects.vue'
import Skills from '../components/Skills.vue'
import Contact from '../components/Contact.vue'
import Footer from '../components/Footer.vue'
</script>

<template>
  <Hero />

  <div class="section-bg">
    <About />
  </div>

  <Career />

  <div class="section-bg">
    <Projects />
  </div>

  <Skills />

  <div class="section-bg">
    <Contact />
  </div>

  <Footer />
</template>

<style scoped>
.section-bg {
  margin-left: calc(50% - 50vw);
  margin-right: calc(50% - 50vw);
  padding-left: calc(50vw - 50%);
  padding-right: calc(50vw - 50%);
  background: #f9fafb;
}
</style>