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
          
            <a href="#aboutme" class="button2">More about me</a>   
          
</div>
  <div class="about-me" id="text-center">
    <h2 class="title-two" id="aboutme">About Me</h2>
    <h3 class="about-me-content">
      My name is Tuya Senff. I thrive on bringing ideas to life. 
      I take pride in crafting innovative solutions with polished user experiences. 
      In my free time I like working on open source projects.</h3>
            <a href="https://docs.google.com/document/d/1ueOS-b_Oom2F544qBvKYseWgjSAWwxTWtovp4EugRZs/edit?usp=sharing" target="_blank" class="button3">My resume</a>   
 <br><br><br>
  </div>

  <div class="recent-projects">
    <h2 class="title-two" id="text-center">Recent Projects</h2>
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
 

 <div id="text-center">
            <a href=" " target="_blanck"><router-link to="/projects" class="button3">My Projects</router-link> </a>
             <br><br><br>
          </div>
    </div>
         </div>
</div>
<footer>
   <div class="footer" id="text-center">
  <h2 class="title-two" id="text-center">Get In Touch</h2>
  <p class="about-me-content">
    I'm currently looking for full-time Front-end Developer opportunities! 
    If you know of any positions available, if you have any questions, or if you just want to say hi,
     please feel free to email me at <a href="mailto: tuya.senff@gmail.com">tuya.senff@gmail.com</a></p>
 
    <div id="text-center">
            <a href=" " target="_blanck"><router-link to="/contact" class="button3">Get in Contact</router-link> </a>
             <br><br><br>
            <p>made by me</p>
          </div>
             </div>
</footer>  

</template>






<script>
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'Home',
  components: {
    Navbar
  },
  
}
</script>
<style scoped>
html {
    scroll-behavior: smooth;
  }
body{
    
    font-size: 100%;
    margin:0;
   padding:0;
   height:100%;
   -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
   
}
.background-color{
	animation-name: backgroundColorPalette;
	animation-duration: 8s;
	animation-iteration-count: infinite;
	animation-direction: alternate;
    animation-timing-function: linear; 
    height: 100vh;
	/* linear is enabled default, it’s not necessary to add it make it work but it can make your code more expressive */
}

@keyframes backgroundColorPalette {
    0% {
		background: #ffd6ff;
	}
    25% {
		background: #e7c6ff;
	}
	50% {
		background: #c8b6ff;
	}
	75% {
		background: #b8c0ff;
	}
	100% {
		background: #bbd0ff;
	}
}


</style>