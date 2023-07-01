<template>
    <div id="tweet" style="display:flex">
      <div><img src="/assets/spacex.jpg"></div>
      
      <div style="min-width: 80%;margin:10px">
        <div>SpaceX @spacex 57min</div>
      <div style="margin: 10px;">Liftoff!!!</div>
      <div id="media"></div>
      <div style="display:flex;justify-content:space-between">
        <message-reply-outline-icon :size="26" style="color:dodgerblue"  class="icon"/>
        <repeat-variant-icon :size="26" style="color:dodgerblue"  class="icon"/>
        <heart-outline-icon :size="26" style="color:dodgerblue"  class="icon"/>
        <poll-icon :size="26" style="color:dodgerblue"  class="icon"/>
        <bookmark-outline-icon :size="26" style="color:dodgerblue"  class="icon"/>
      </div>
      </div>
      
    </div>
</template>
<script>

import MessageReplyOutlineIcon from 'vue-material-design-icons/EmoticonOutline.vue';
import RepeatVariantIcon from 'vue-material-design-icons/RepeatVariant.vue';
import HeartOutlineIcon from 'vue-material-design-icons/HeartOutline.vue';
import PollIcon from 'vue-material-design-icons/Poll.vue';
import BookmarkOutlineIcon from 'vue-material-design-icons/BookmarkOutline.vue';

export default{
    components: {
        MessageReplyOutlineIcon, RepeatVariantIcon, HeartOutlineIcon, PollIcon,
        BookmarkOutlineIcon
    }
}
</script>
<style scoped>
  img{
    width: 40px;
    border-radius: 50%;
  }
</style>