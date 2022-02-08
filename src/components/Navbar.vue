<template>

<div class="background-color">

<div id="nav">
       <router-link to="/contact">CONTACT</router-link>  
        <a href="https://docs.google.com/document/d/1ueOS-b_Oom2F544qBvKYseWgjSAWwxTWtovp4EugRZs/edit?usp=sharing">RESUME</a>  
        <router-link to="/projects">PROJECTS</router-link> 
        <router-link to="/">HOME</router-link> 
   
       
</div>
 </div>
</template>

<script>
export default {

}
</script>

<style scoped>


#nav {
  color: #ffffff;
 
}

#nav a {
  font-size: 25px;
  text-decoration: none;  
  color: #fdfdfd;
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