<template>
  <div class="home">
    <img alt="tuya-senff-img" src="../assets/IMG_2130.jpeg">
    <h2>Hey there, </h2>
    <p>I'm a frontend developer, designer who has been building for the web in some capacity since 2015. I like to craft solid and scalable frontend products with great user experiences.</p>
    <p>I thrive on bringing ideas to life. I take pride in crafting innovative solutions with polished user experiences. This whilst possessing a keen eye for design, accessibility, performance, and well-structured code.</p>
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
img {
  width: 25%;
}
p {
  padding: 10px;
}
</style>