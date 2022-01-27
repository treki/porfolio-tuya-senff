<template>
<div id="nav">
 <router-link to="/">HOME</router-link> |
    <router-link to="/skills">SKILLS</router-link> |
      <router-link to="/contact">CONTACT</router-link>
       
</div>
 
</template>

<script>
export default {

}
</script>

<style scoped>
#nav {
  
  padding: 30px;
}

#nav a {
  text-decoration: none;
  font-weight: bold;
  color: #2c3e50;
}
#nav a:hover{
  color: #df6ebf;
}


#nav a.router-link-exact-active {
  color: #c91c98;
  
}
</style>