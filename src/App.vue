<template>
  <!-- <HeaderComponent/>
  <NavComponent /> -->
  <MainPageComponent/>
</template>

<script>
import MainPageComponent from './components/pages/MainPage.vue';
// import HeaderComponent from './components/HeaderComponent.vue';
// import NavComponent from './components/NavComponent.vue';
export default {
  name: 'App',
  components: {
    MainPageComponent
    // HeaderComponent,
    // NavComponent,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  /* color: #2c3e50;
  margin-top: 60px; */
}
p {
  margin-bottom: 0;
}
</style>
