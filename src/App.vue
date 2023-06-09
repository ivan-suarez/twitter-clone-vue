

<template id="template">
  <div id="tmp">
    <div id="left">
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
  <div id="profile-menu">
        <div id="profile-picture"></div>
        <div>Elon Musk</div>
        <div>@elonmusk</div>
      </div>
    </div>
    
  <div id="content">
    <div>Home</div>
    <div>What is happening?!
      
      <div>
        <image-outline-icon :size="26" class="icon"/>
        <file-gif-box-icon :size="26" class="icon"/> 
        <poll-icon :size="26" class="icon"/> 
        <emoticon-outline-icon :size="26" class="icon"/> 
        <timer-outline-icon :size="26" class="icon"/>
        <button>Tweet</button>
      </div>
    </div>
    <div id="tweet">
      <div>SpaceX</div>
      <div>Liftoff!</div>
      <div id="media"></div>
      <div>
        <message-reply-outline-icon :size="26" class="icon"/>
        <repeat-variant-icon :size="26" class="icon"/>
        <heart-outline-icon :size="26" class="icon"/>
        <poll-icon :size="26" class="icon"/>
        <bookmark-outline-icon :size="26" class="icon"/>
      </div>
    </div>
  </div>
  <div id="ads">
    <div>Search Twitter</div>
    <div>What's happening</div>
    <div>Who to follow</div>
  </div>
  </div>
  
  
</template>

<style>
#tmp{
  display: flex;
}

#content{
  border-style: solid;
  border-color: lightgray;
  flex: 1;
  min-height: 100vh;
}

#tweet{
  border-style: solid;
  border-color: lightgray;
}

#left{
  display: flex;
  flex: 1;
  min-height: 100vh;
  justify-content: space-between;
  flex-direction: column;
  align-items: flex-end;
}

#nav-bar{
  display: flex;
  flex-direction: column;
  
}

#ads{
  flex: 1;
}
#profile-menu{
  justify-content: flex-end;
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

import ImageOutlineIcon from 'vue-material-design-icons/ImageOutline.vue';
import FileGifBoxIcon from 'vue-material-design-icons/FileGifBox.vue';
import PollIcon from 'vue-material-design-icons/Poll.vue';
import EmoticonOutlineIcon from 'vue-material-design-icons/EmoticonOutline.vue';
import TimerOutlineIcon from 'vue-material-design-icons/TimerOutline.vue';

import MessageReplyOutlineIcon from 'vue-material-design-icons/EmoticonOutline.vue';
import RepeatVariantIcon from 'vue-material-design-icons/RepeatVariant.vue';
import HeartOutlineIcon from 'vue-material-design-icons/HeartOutline.vue';

export default {
    components: { TwitterIcon, HomeIcon, SearchWebIcon, BellIcon, EmailOutlineIcon, ListBoxOutlineIcon, 
      BookmarkOutlineIcon,CheckDecagramOutlineIcon, AccountOutlineIcon, SettingsHelperIcon, ImageOutlineIcon,
      FileGifBoxIcon, PollIcon, EmoticonOutlineIcon, TimerOutlineIcon, MessageReplyOutlineIcon, RepeatVariantIcon,
      HeartOutlineIcon},
}
</script>
