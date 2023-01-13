<template>
  <NavBar/>
  <Hero/>
  <MainCard/>
  <Foot/>
</template>

<script>
import NavBar from './components/nav-bar.vue';
import Hero from './components/hero.vue';
import MainCard from './components/main-card.vue';
import Foot from './components/footer.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    Hero,
    MainCard,
    Foot
  }
}
</script>

<style>
body {
  background-color: #f5f5f5e3;
}
</style>
