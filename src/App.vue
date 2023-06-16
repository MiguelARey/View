<template>
  <!-- <HeaderComponent/>
  <NavComponent /> -->
  <!-- <MainPageComponent/> -->
  <!-- <LoginPageComponent/> -->
  <SignUpPageComponent/>
</template>

<script>
import SignUpPageComponent from './components/pages/SignUpPage.vue'
// import LoginPageComponent from './components/pages/LoginPage.vue'
// import MainPageComponent from './components/pages/MainPage.vue';
// import HeaderComponent from './components/HeaderComponent.vue';
// import NavComponent from './components/NavComponent.vue';
export default {
  name: 'App',
  components: {
    SignUpPageComponent
    // LoginPageComponent
    // MainPageComponent
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
