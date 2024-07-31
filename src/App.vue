<template>
  <div id="app">
    <NavBarComponent />
    <HomePageComponent />
  </div>
</template>

<script>
import NavBarComponent from './components/NavBarComponent.vue';
import HomePageComponent from './views/HomePageComponent.vue';

export default {
  name: 'App',
  components: {
    NavBarComponent,
    HomePageComponent
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
