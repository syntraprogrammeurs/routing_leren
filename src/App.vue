<template>
  <div id="app">
    <Navbar></Navbar>
    <router-view></router-view>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'app',
  components: {
    Navbar
  }
}
</script>

<style>
  *{
    font-family: 'Raleway', sans-serif;
  
  }
  body{
    background:lightblue;
  }

</style>
