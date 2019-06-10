<template>
  <div id="app">
    <HelloWorld />
    <Programs />
    <h2>Navbar</h2>
    <LandingPage />
    <br><hr>
    <Subject />

    
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Programs from './components/Programs.vue'
import LandingPage from './components/LandingPage'
import Subject from './components/Subject.vue'




export default {
  name: 'app',
  components: {
    HelloWorld,
    Programs,
    LandingPage,
    Subject
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
