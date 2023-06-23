<template>
    <div id="nav-bar">
        <div id="logo">
          <twitter-icon :size="36" class="icon"/>
        </div>
        <div class="nav-bar-item"><home-icon :size="36" class="icon"/> <span>Home</span></div>
        <div class="nav-bar-item"><search-web-icon :size="36" class="icon"/><span>Explore</span> </div>
        <div class="nav-bar-item"><bell-icon :size="36" class="icon"/><span>Notifications</span></div>
        <div class="nav-bar-item"><email-outline-icon :size="36" class="icon"/><span>Messages</span></div>
        <div class="nav-bar-item"><list-box-outline-icon :size="36" class="icon"/><span>Lists</span></div>
        <div class="nav-bar-item"><bookmark-outline-icon :size="36" class="icon"/><span>Bookmarks</span></div>
        <div class="nav-bar-item"><check-decagram-outline-icon :size="36" class="icon"/><span>Verified</span></div>
        <div class="nav-bar-item"><account-outline-icon :size="36" class="icon"/><span>Profile</span></div>
        <div class="nav-bar-item"><settings-helper-icon :size="36" class="icon"/><span>Options</span></div>
        <button>Tweet</button>
      
    </div>
</template>
<style scoped>
    #nav-bar{
    display: flex;
    flex-direction: column;
  }
    .nav-bar-item{
      display: flex;
      align-items: center;
      gap: 10px;
      padding: 10px;
      font-size: 20px;
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