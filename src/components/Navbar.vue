<template>

<div class="background-color-nav">

<div id="nav">
       <router-link to="/contact">CONTACT</router-link>  
        <a href="https://docs.google.com/document/d/1ueOS-b_Oom2F544qBvKYseWgjSAWwxTWtovp4EugRZs/edit?usp=sharing" target="_blank">RESUME</a>  
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



#nav a {
  font-size: 1.5rem;
  text-decoration: none;  
  color: #0c0c0c;
  padding: 20px 20px;
  float: right;
  line-height: 30px;
  margin: 0;

}
#nav a:hover{
  color: #263f8f;
}


#nav a.router-link-exact-active {
  background-color: #728de6;
  border-radius: 8px;
  
}

</style>