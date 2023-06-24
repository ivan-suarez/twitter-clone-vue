<template>
    <div id="sidebar">
        <search></search>
        <trending-bar></trending-bar>
        <who-to-follow></who-to-follow>
    </div>
    
</template>
<script>
import Search from './Search.vue';
import WhoToFollow from './WhoToFollow.vue'
import TrendingBar from './TrendingBar.vue'


export default {
    components: {Search, WhoToFollow, TrendingBar},
}

</script>
<style scoped>
    #sidebar{
        
        width: 400px;
        display: flex;
        flex-direction: column;
        gap: 20px;
    }
</style>
