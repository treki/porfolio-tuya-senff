<template>
    <div class="skill-title">
        <h2> Skills and Tools</h2>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>Javascript</li>
            <li>Vue</li>
        </ul>
    </div>

    <div class="skill-title" v-for="skill in skills" :key="skill.id">
      <router-link :to="{name: 'Resume', params: { id: skill.id }}">
          <h2>{{ skill.title }}</h2>
          </router-link>
    </div>
    
</template>

<script>
export default {
    data() {
        return {
            skills: [
                {title: 'My Resume', id:1, details: 'My Resume'},                
            ]
        }
    }
}
</script>
<style>
.skill-title h2{
    background: #f4f4f4;
    padding: 20px;
    border-radius: 10px;
    margin: 10px auto;
    max-width: 500px;
    cursor: pointer;
    color: #444;
}
.skill-title h2:hover{
    background: #ddd;
}
.skill-title a{
    text-decoration: none;
}
.skill-title ul li{
    text-decoration: none;
}
</style>