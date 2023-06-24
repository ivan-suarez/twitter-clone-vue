<template>
    <div style="display:flex; background-color: lightgray;padding:5px">
        <SearchWebIcon></SearchWebIcon>
        <input placeholder="Search Twitter" style="width:100%;background-color: lightgray;">
    </div>
    
</template>
<script>
import SearchWebIcon from 'vue-material-design-icons/SearchWeb.vue';
export default {
    components: {
        SearchWebIcon
    }
}
</script>