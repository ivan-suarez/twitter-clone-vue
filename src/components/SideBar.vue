<template>
    <div id="sidebar">
        <trending-bar></trending-bar>
        <who-to-follow></who-to-follow>
    </div>
    
</template>
<script>



import WhoToFollow from './WhoToFollow.vue'
import TrendingBar from './TrendingBar.vue'


export default {
    components: { WhoToFollow, TrendingBar},
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
