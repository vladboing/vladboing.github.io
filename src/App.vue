<template>
  <div id="app">
    <Header></Header>
    <About></About>
    <Works></Works>
    <Skills></Skills>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import About from './components/About.vue'
import Works from './components/Works.vue'
import Skills from './components/Skills.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'app',
  components: {
    Header,
    About,
    Works,
    Skills,
    Footer
  }
}
</script>
