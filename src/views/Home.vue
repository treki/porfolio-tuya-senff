<template>
  <div class="home">
    <img alt="tuya-senff-img" src="../assets/background-t.png ">
    <h1>  </h1>
    <p></p>
    
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'Home',
  components: {
    Navbar
  }
}
</script>
<style>

img{
  padding: 100px;
}
.home h1{
  color: #ff6f69;
}
p {
  padding: 10px;
}
</style>