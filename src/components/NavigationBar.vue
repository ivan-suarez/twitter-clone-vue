<template>
    <div id="nav-bar">
        <div id="logo">
          <twitter-icon :size="36" class="icon"/>
        </div>
        <div><home-icon :size="36" class="icon"/> Home</div>
        <div><search-web-icon :size="36" class="icon"/> Explore</div>
        <div><bell-icon :size="36" class="icon"/>Notifications</div>
        <div><email-outline-icon :size="36" class="icon"/>Messages</div>
        <div><list-box-outline-icon :size="36" class="icon"/>Lists</div>
        <div><bookmark-outline-icon :size="36" class="icon"/>Bookmarks</div>
        <div><check-decagram-outline-icon :size="36" class="icon"/>Verified</div>
        <div><account-outline-icon :size="36" class="icon"/>Profile</div>
        <div><settings-helper-icon :size="36" class="icon"/>Options</div>
        <button>Tweet</button>
      
    </div>
</template>
<style scoped>
    #nav-bar{
    display: flex;
    flex-direction: column;
  }
</style>

<script>
import TwitterIcon from 'vue-material-design-icons/Twitter.vue';
import HomeIcon from 'vue-material-design-icons/Home.vue';
import SearchWebIcon from 'vue-material-design-icons/SearchWeb.vue';
import BellIcon from 'vue-material-design-icons/Bell.vue';
import EmailOutlineIcon from 'vue-material-design-icons/EmailOutline.vue';
import ListBoxOutlineIcon from 'vue-material-design-icons/ListBoxOutline.vue';
import BookmarkOutlineIcon from 'vue-material-design-icons/BookmarkOutline.vue';
import CheckDecagramOutlineIcon from 'vue-material-design-icons/CheckDecagramOutline.vue';
import AccountOutlineIcon from 'vue-material-design-icons/AccountOutline.vue';
import SettingsHelperIcon from 'vue-material-design-icons/SettingsHelper.vue';



export default {
    components: { TwitterIcon, HomeIcon, SearchWebIcon, BellIcon, EmailOutlineIcon, ListBoxOutlineIcon, 
      BookmarkOutlineIcon,CheckDecagramOutlineIcon, AccountOutlineIcon, SettingsHelperIcon},
}
</script>