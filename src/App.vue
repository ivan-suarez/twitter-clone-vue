

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
    <h2>Home</h2>
    <div style="display:flex;flex-direction:column;justify-content: space-between;min-height: 100px;">
      <div style="font-size: x-large;">What is happening?!</div>
      
      <div style="display:flex;justify-content: space-between;">
        <div>
          <image-outline-icon :size="26" style="color:dodgerblue" class="icon"/>
        <file-gif-box-icon :size="26" style="color:dodgerblue" class="icon"/> 
        <poll-icon :size="26" style="color:dodgerblue" class="icon"/> 
        <emoticon-outline-icon :size="26" style="color:dodgerblue" class="icon"/> 
        <timer-outline-icon :size="26" style="color:dodgerblue" class="icon"/>
        </div>
        
        <button>Tweet</button>
      </div>
    </div>
    
    <tweet></tweet>
    <tweet></tweet>
    <tweet></tweet>
    <tweet></tweet>
    <tweet></tweet>
    <tweet></tweet>
    <tweet></tweet>
    <tweet></tweet>
    <tweet></tweet>
  </div>
  <div id="right">
    <side-bar></side-bar>
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
  flex: 0.75;
  min-height: 100vh;
  margin-left: 30px;
  margin-right: 30px;
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

button{
  background-color: dodgerblue;
  color: white;
  border-radius: 9999px;
  min-height: 40px;
  min-width: 80px;
  font-weight: 900;
}

</style>

<script>


import ImageOutlineIcon from 'vue-material-design-icons/ImageOutline.vue';
import FileGifBoxIcon from 'vue-material-design-icons/FileGifBox.vue';
import PollIcon from 'vue-material-design-icons/Poll.vue';
import EmoticonOutlineIcon from 'vue-material-design-icons/EmoticonOutline.vue';
import TimerOutlineIcon from 'vue-material-design-icons/TimerOutline.vue';

import Tweet from './components/Tweet.vue'
import NavigationBar from './components/NavigationBar.vue'

import SideBar from './components/SideBar.vue';

export default {
    components: {ImageOutlineIcon,
      FileGifBoxIcon, PollIcon, EmoticonOutlineIcon, TimerOutlineIcon, Tweet, NavigationBar, SideBar},
}
</script>
