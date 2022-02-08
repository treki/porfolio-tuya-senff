<template>
<div class="background-color">
  <div class="text-center">
     <h1 class="title"> Tuya Senff</h1>
      <h3 class="lead-typist">Front-End Developer</h3>
          <div class="social-icons">
            <a target="_blank" href="https://github.com/treki"  >
            <img class="icon" src="../assets/GitHub-Mark-Light-32px.png">
            </a>   
           
            <a target="_blank" href="https://www.linkedin.com/"  >
            <img class="icon" src="../assets/linkedin.png">
            
            </a>   
             <a target="_blank" href="https://github.com/treki"  >
            <img class="icon" src="../assets/GitHub-Mark-Light-32px.png">
            </a>   
           
            <a target="_blank" href="https://www.linkedin.com/"  >
            <img class="icon" src="../assets/linkedin.png">
            
            </a>   
    
          </div>
          <div class="about-me-button">
            <button class="about-me-button">More about me</button>
          
          </div>
  </div>
</div>
  <div class="about-me">
    <h1 class="title">About Me</h1>
    <h2>My name is Tuya Senff. In my free time I like working on open source projects.</h2>


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
<style scoped>

.text-center{
  text-align: center!important;
}
a {
  text-decoration: none;
  color: #000000;

}

.icon{
  color: #ffffff;
  width:57px;
  padding: 10px;;
}
.icon:hover{
  color:rgb(255, 251, 251);
}
a:hover{
  color: #6b6b6b;
}
.icons img{
  width: 30px;
  height: auto;
  padding: 20px;
  
}
h1 .title{
  color: #000000;
}

p {
  padding: 10px;
}

</style>