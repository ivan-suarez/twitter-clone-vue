<template>
   <div id ="ads">
    <div>Search Twitter</div>
    <div><h2>What's happening</h2>
      <Trend></Trend>
      <Trend></Trend>
      <Trend></Trend>
    </div>
   </div> 
    
</template>
<style scoped>
  
</style>
<script>



import Trend from './Trend.vue';

export default{
    components: {
        Trend
    }
}
</script>
