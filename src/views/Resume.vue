<template>
   
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
   <link href="https://fonts.googleapis.com/css2?family=Karla&family=Source+Sans+3:wght@500&display=swap" rel="stylesheet">
    <title>Resume</title>
  </head>
  <body>
    
    <main >
       
      <header>
        <h1>TUYA SENFF</h1>
        <div class="contact-info">
          <span>tuya.senff@gmail.com</span>
          <span>425-446-1744</span>
          <span>Conroe TX, USA</span>
        </div>
        <div class="contact-info"></div>
      </header>
      <section class="content-section">
        <h1>Objective</h1>
        <p>
          To obtain a full-time position in the web development field where I can
          use my skills as a frontend developer skills. I thrive on bringing ideas to life. 
          I take pride in crafting innovative solutions with polished user experiences. 
          This whilst possessing a keen eye for design, accessibility, performance, and well-structured code.
        </p>
      </section>
     
         <section class="content-section">
        <h1>Skills</h1>
        <div class="skills">
        <ul>
                        <li><p>HTML5 & CSS3</p></li>
                        <li><p>Javascript, Vue</p></li>
                        <li><p>Git & GitHub</p></li>
                        <li><p>Linux, Bash/Shell</p></li>
            
        </ul>
        </div>
      </section>

      <section class="content-section">
        <h1>Certificates</h1>
        <div class="multicolumn">
          <div class="experience-container">
            <h2>
              <span class="heavy-text">freeCodeCamp</span> November 8, 2021
            </h2>
            <p>JavaScript Algorithims and Data Structure</p>            
          </div>

          <div class="experience-container">
            <h2>
              <span class="heavy-text">freeCodeCamp</span> August 3, 2021
            </h2>    
                <p>Responsive WebDesign</p> 
          </div>
         
          <div class="experience-container">
            <h2>
              <span class="heavy-text">Vue School</span> January 3, 2022 - present
            </h2>    
                <p>Responsive WebDesign</p> 
          </div>
        </div>
      </section>


      <section class="content-section">
        <h1>Experience</h1>
        <div class="multicolumn">
          <div class="experience-container">
            <h2>
              <span class="heavy-text">Software Developer</span> June 2019 –
              Present
            </h2>
            <div>
              <span>Silverline</span> | Omaha, Nebraska
            </div>
      
          </div>
         
        </div>
      </section>

      
    </main>
  </body>
</html>

</template>


<style scoped>

body {
  background-color: rgb(216, 216, 216);
  line-height: 1.5;
  margin: 10px auto;
  max-width: 1200px;
}

main {
  margin: 0 auto;
  box-sizing: border-box;
  padding: 0.5in;
  width: 8.5in;
  height: 11in;
  background-color: white;
  box-shadow: 0 3px 8px -3px rgba(0, 0, 0, 0.7);
  font-family: 'Karla', sans-serif;
  font-family: 'Source Sans 3', sans-serif;

  color: hsl(0, 0%, 20%);
}

h1,
h2,
p,
ul {
  margin: 2px;
}



.contact-info {
  display: center;
  color: #6b6b6b;
  font-size: 20px;
}

.contact-info span::after {
  content: "   ";
  margin: 0 4px;
}

.contact-info span:last-child::after {
  content: none;
}

.content-section {
  margin-top: 1.5rem;
}

.content-section h1 {
  font-size: 20px;
  text-transform: uppercase;
}

.content-section p {
  color: #2e2d2d;
  font-size: 18px;
}

.multicolumn {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2rem;
}

.experience-container h2 {
  font-weight: normal;
  font-size: 1rem;
}

.heavy-text {
  font-weight: bold;
}
.skills ul li{
    list-style-type: none;
   float: left;
   clear: right;
}



@media print {
  html {
    height: 11in;
    width: 8.5in;
    overflow: hidden;
  }

  body {
    margin: 0;
  }
 .canvas-container {
    width: 100%;
    box-shadow: none;
  }
  main {
    width: 100%;
    box-shadow: none;
  }

  button {
    display: none;
  }

  .download-link {
    display: none;
  }
}


</style>