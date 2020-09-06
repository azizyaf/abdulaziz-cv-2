<template>
  <div>
        <ul class="list-group">
        <li 
            v-for="skill in dsSkills" 
            :key="skill.id"
            class="list-group-item list-group-item-warning"
            >{{ skill }}</li>
        </ul>
  </div>
</template>

<script>
export default {
    data: function(){
        return{
            dsSkills: ['Database and SQL For Data Science', 'Data Visualization With Python', 'Data Science Methodology', 'Machine Learning with Python', 'Data Analysis with Python']
        }
    }

}
</script>

<style scoped>



</style>