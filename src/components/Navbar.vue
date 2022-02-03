<template>
<link rel="preconnect" href="https://fonts.googleapis.com"> 
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin> 
<link href="https://fonts.googleapis.com/css2?family=Karla&family=Source+Sans+3:wght@500&display=swap" rel="stylesheet">
<div class="logo">

    <a href="">
     <img class="profile-logo" src="../assets/logo-senff.png" alt="Profile logo">
    </a>
</div>
<div id="nav">
       <router-link to="/contact">CONTACT</router-link>  
        <router-link to="/resume">RESUME</router-link>  
        <router-link to="/projects">PROJECTS</router-link> 
        <router-link to="/">HOME</router-link> 
   
       
</div>
 
</template>

<script>
export default {

}
</script>

<style scoped>
#nav{
    font-family: 'Karla', sans-serif;
font-family: 'Source Sans 3', sans-serif;
}
.profile-logo{
    padding: 10px;
   float:left;
   clear:right;
   margin-left:20px
}
#nav {

  padding: 55px;
}

#nav a {
font-size: 25px;
  text-decoration: none;
  
  color: #000000;
  padding-left: 30px;
  float: right;
  line-height: 30px;

}
#nav a:hover{
  color: #6b6b6b;
}


#nav a.router-link-exact-active {
  color: #6b6b6b;
  
}
</style>