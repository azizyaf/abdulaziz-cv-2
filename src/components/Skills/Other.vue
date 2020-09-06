<template>
  <div>
        <ul class="list-group">
        <li 
            v-for="other in others" 
            :key="other.id"
            class="list-group-item list-group-item-warning"
            >{{ other }}</li>
        </ul>
  </div>
</template>

<script>
export default {
    data: function(){
        return{
            others: ['MySQL', 'Oracle Database','Professional Report Writing']
        }
    }

}
</script>

<style scoped>
</style>