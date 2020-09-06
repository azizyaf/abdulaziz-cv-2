<template>
  <div>
    <transition
      appear
      enter-active-class="animated bounceInDown">
      <Intro />
    </transition>
    <about-me></about-me>
    <div class="container">
      <div class="text-center">
        <button @click="selectedComponent = 'Education'" class="btn btn-outline-warning btn-lg">Education</button>
        <button @click="selectedComponent = 'Skills'" class="btn btn-outline-warning btn-lg">Skills</button>
        <button @click="selectedComponent = 'Contact'" class="btn btn-outline-warning btn-lg">Contact & More</button>
      </div>
      
      <div class="container">
        <component :is="selectedComponent"></component>
      </div>
    </div>
    <Footer/>
  </div>
    
</template>

<script>
import Intro from './components/Intro.vue'
import AboutMe from './components/AboutMe.vue'
import Education from './components/Education.vue'
import Skills from './components/Skills.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'

export default {
  data: function(){
    return{
      selectedComponent: 'Education'
    }
  },
  components: {
    Intro,
    AboutMe,
    Education,
    Skills,
    Contact,
    Footer
  }
}
</script>

<style>

button{
  margin: 20px 10px 20px 10px;
}


</style>
