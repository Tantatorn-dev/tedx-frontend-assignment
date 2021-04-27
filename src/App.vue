<template>
  <div id="app">
    <NavBar />
    <MainSection />
    <Personality />
  </div>
</template>

<script>
import NavBar from './components/NavBar'
import MainSection from "./components/MainSection";
import Personality from "./components/Personality";

export default {
  name: 'App',
  components: {
    NavBar,
    MainSection,
    Personality,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
