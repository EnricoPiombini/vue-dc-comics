<template>
  <div id="app">
    <div class="container">
      <TheNavbar />
      <TheCard />
      <TheBannerBlue />
      <TheFooter />
      <TheBannerSignUp />
    </div>
  </div>


</template>

<script>
import TheNavbar from './components/TheNavbar.vue';
import TheBannerBlue from './components/TheBannerBlue.vue';
import TheFooter from './components/TheFooter.vue';
import TheBannerSignUp from './components/TheBannerSignUp.vue';
import TheCard from './components/TheCard.vue';


export default {
  name: 'App',
  components: {
    TheNavbar,
    TheCard,
    TheBannerBlue,
    TheFooter,
    TheBannerSignUp,

  }
}
</script>

<style lang="scss">
#app {
  // font-family: Avenir, Helvetica, Arial, sans-serif;

  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
