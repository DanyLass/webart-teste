<template>
  <div id="app">
    <HomeMobile />
    <HomeDesktop />
  </div>
</template>

<script>

import './styles/global.css';
import HomeMobile from './views/HomeMobile.vue';
import HomeDesktop from './views/HomeDesktop.vue';
export default {
  name: 'App',
  components: {
    HomeMobile,
    HomeDesktop
  }
}
</script>

<style scoped>

</style>


