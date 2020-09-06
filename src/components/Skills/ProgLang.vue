<template>
  <div>
        <ul class="list-group">
        <li 
            v-for="language in languages" 
            :key="language.id"
            class="list-group-item list-group-item-warning"
            >{{ language }}</li>
        </ul>
  </div>
</template>

<script>
export default {
    data: function(){
        return{
            languages: ['JavaScript', 'PHP','SQL', 'C++', 'C#', 'Java']
        }
    }

}
</script>

<style scoped>
</style>