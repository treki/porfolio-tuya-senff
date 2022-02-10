<template>
<div class="background-color" id="text-center">
     <h1 class="title"> Tuya Senff</h1>
      <h3 class="lead-typist">Front-End Developer</h3>
          <div class="social-icons">
            <a target="_blank" href="https://github.com/treki"  >
            <img class="icon" src="../assets/GitHub-Mark-Light-32px.png">
            </a>   

             <a target="_blank" href="https://github.com/treki"  >
            <img class="icon" src="../assets/GitHub-Mark-Light-32px.png">
            </a>   
              
          </div>
          <div class="my-button" >
            <a href="#aboutme"><button class="my-button">More about me</button></a>   
          </div>
</div>
  <div class="about-me" id="text-center">
    <h2 class="title-second" id="aboutme">About Me</h2>
    <h3 class="about-me-content">
      My name is Tuya Senff. I thrive on bringing ideas to life. 
      I take pride in crafting innovative solutions with polished user experiences. 
      In my free time I like working on open source projects.</h3>
          <div class="my-button" >
            <a href="https://docs.google.com/document/d/1ueOS-b_Oom2F544qBvKYseWgjSAWwxTWtovp4EugRZs/edit?usp=sharing" target="_blank"><button class="my-button">Resume</button></a>   
          </div>
  </div>

  
    <h2 class="title-third" id="text-center">Recent Projects</h2>
    <div class="row">
      <div class="column">
    <div class="card">
      <div class="card-body">
        <h3 class="card-title">Modal</h3>
          <p class="card-text">
            Insipied by the matrix a simple modal example. I used vue components to inject dynamic data into my template. I also used methods and props to react to events</p>
                    <div class="my-button" >
            <a href="https://github.com/treki/modal-project/archive/master.zip" target="_blank">
            <button type="button" class="my-button-projects"> 
              <img src="../assets/slice1.png"/>
                <span>Clone Project</span>
              </button></a>   
           </div>

            <div class="my-button" >
            <a href="https://github.com/treki/modal-project" target="_blank">
            <button type="button" class="my-button-projects"> 
              <img src="../assets/slice1.png"/>
                <span>Repo</span>
              </button></a>   
           </div>
      <br><br><hr>
            <h5>Languages:</h5><p class="languages">
               VUE, VUE CLI,  HTML, CSS </p>
            <p class="card-text">Updated January 2022</p>
          </div>   
    </div>
      </div>

      <div class="column">
        <div class="card">
      <div class="card-body">
        <h3 class="card-title">Covid-19 Tracker</h3>
          <p class="card-text">
            A realtime global Covid-19 tracker. I used axios and promises in javascript to send and recieve xml http request from the browser.</p>
                    <div class="my-button" >
            <a href="https://github.com/treki/Covid-19-Tracker/archive/master.zip" target="_blank">
            <button type="button" class="my-button-projects"> 
              <img src="../assets/slice1.png"/>
                <span>Clone Project</span>
              </button></a>   
           </div>

            <div class="my-button" >
            <a href="https://github.com/treki/Covid-19-Tracker" target="_blank">
            <button type="button" class="my-button-projects"> 
              <img src="../assets/slice1.png"/>
                <span>Repo</span>
              </button></a>   
           </div>
      <br><br><hr>
            <h5>Languages:</h5><p class="languages">
              JavaScript, Node, HTML, CSS, VUE CLI</p>
            <p class="card-text">November 2021</p>
          </div>   
    </div>
      </div>
    </div>
   <div class="about-me" id="text-center">
  <h2 class="title-fourth" id="text-center">Get In Touch</h2>
  <p>
    I'm currently looking for full-time Front-end Developer opportunities! 
    If you know of any positions available, if you have any questions, or if you just want to say hi,
     please feel free to email me at, tuya.senff@gmail.com.</p>
    </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'Home',
  components: {
    Navbar,
  
  },
  
}
</script>
<style scoped>




</style>