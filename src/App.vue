

<template id="template">
  <div id="tmp">
    <div id="left">
      <navigation-bar></navigation-bar>
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
    
    <tweet></tweet>
  </div>
  <div id="right">
    <trending-bar></trending-bar>
    <who-to-follow></who-to-follow>
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



#right{
  flex: 1;
}
#profile-menu{
  justify-content: flex-end;
}

</style>

<script>


import ImageOutlineIcon from 'vue-material-design-icons/ImageOutline.vue';
import FileGifBoxIcon from 'vue-material-design-icons/FileGifBox.vue';
import PollIcon from 'vue-material-design-icons/Poll.vue';
import EmoticonOutlineIcon from 'vue-material-design-icons/EmoticonOutline.vue';
import TimerOutlineIcon from 'vue-material-design-icons/TimerOutline.vue';

import Tweet from './components/Tweet.vue'
import WhoToFollow from './components/WhoToFollow.vue'
import TrendingBar from './components/TrendingBar.vue'
import NavigationBar from './components/NavigationBar.vue'

export default {
    components: {ImageOutlineIcon,
      FileGifBoxIcon, PollIcon, EmoticonOutlineIcon, TimerOutlineIcon, Tweet, WhoToFollow, TrendingBar, NavigationBar},
}
</script>
