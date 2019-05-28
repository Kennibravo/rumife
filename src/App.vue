<template>
  <v-app> 
      <app-nav></app-nav>
      <app-carousel></app-carousel>
  <v-content>
    <v-container fluid>
      <router-view>

      </router-view>
    </v-container>
  </v-content>
  <v-footer app></v-footer>
</v-app>
</template>

<script>
import AppNav from './components/app-components/app-nav.vue';
import AppCarousel from './components/app-components/app-carousel.vue';

export default {
  name: 'App',
  components: {AppNav, AppCarousel},
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
