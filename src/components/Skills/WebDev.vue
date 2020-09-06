<template>
  <div>
        <ul class="list-group">
        <li 
            v-for="skill in wdSkills" 
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
            wdSkills: ['HTML', 'CSS', 'JavaScript', 'Vue.js', 'React.js',  'PHP', 'Bootstrap']
        }
    }

}
</script>

<style scoped>

</style>