<template>
<link rel="preconnect" href="https://fonts.googleapis.com"> 
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin> 
<link href="https://fonts.googleapis.com/css2?family=Karla&family=Source+Sans+3:wght@500&display=swap" rel="stylesheet">
<Navbar />
  <router-view/>
</template>

<script>
import Navbar from '@/components/Navbar.vue'

export default {
  
  components: {
    Navbar
  }
}
</script>
<style>
#app {
  font-family: 'Karla', sans-serif;
  font-family: 'Source Sans 3', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  text-transform: uppercase;
  color: #3d3d3d;
}

a:hover{
  color: #6b6b6b;
}
</style>
