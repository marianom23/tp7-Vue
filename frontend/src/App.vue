<template>
  <div id="app">
    <NavBarTop/>
    <router-view/>
  </div>
</template>


<script>
import NavBarTop from './components/NavBarTop.vue'


  export default {
    name: 'App',
    components: {
      NavBarTop
    }
  }
</script>

<style>

</style>
