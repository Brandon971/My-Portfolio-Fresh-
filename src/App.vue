<template>
  <Navbar />
  <Home />
  <About />
  <Testimonials />
  <Skills />
  <Resume />
  <Projects/>
  <Contact/>
  <FooterB/>

</template>

<script>
// @ is an alias to /src
import About from '@/components/About.vue'
import Home from '@/components/Home.vue'
import Navbar from '@/components/Nav.vue'
import Testimonials from '@/components/Testimonials.vue'
import Skills from '@/components/Skills.vue'
import Resume from '@/components/Resume.vue'
import Projects from '@/components/Projects.vue'
import Contact from '@/components/ContactMe.vue'
import FooterB from '@/components/Footer.vue'

export default {
  components: {
    Home,
    About,
    Navbar,
    Testimonials,
    Skills,
    Resume,
    Projects,
    Contact,
    FooterB
    }
}
</script>
<style>
*,
*::after,
::before{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body{
  width:100vw;
  background-color: black;
  overflow-x: hidden;
}

</style>
