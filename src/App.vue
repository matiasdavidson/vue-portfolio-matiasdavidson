<template>
  <div id="app">

    <nav-bar />

    <header class="masthead">
      <site-header />
    </header>
    <about-me />
    <recent-experience />
    <portfolio />
    <education />
    <skills />
    <footer style="background-color: black;">
      <site-footer />
    </footer>
  </div>
</template>

<script>

import Portfolio from './components/Portfolio';
import NavBar from './components/NavBar';
import SiteHeader from './components/SiteHeader';
import AboutMe from './components/AboutMe';
import RecentExperience from './components/RecentExperience';
import Education from './components/Education';
import Skills from './components/Skills';
import SiteFooter from './components/SiteFooter.vue';

export default {
  name: 'app',
  components: {
    Portfolio,
    NavBar,
    SiteHeader,
    AboutMe,
    RecentExperience,
    Education,
    Skills,
    SiteFooter
  }
}
</script>

<style>
#app,
    RecentExperience {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

body {
  background: black;
}
</style>
