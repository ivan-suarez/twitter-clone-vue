<template>
    <div id="tweet">
      <div>SpaceX</div>
      <div>Liftoff!!!</div>
      <div id="media"></div>
      <div>
        <message-reply-outline-icon :size="26" class="icon"/>
        <repeat-variant-icon :size="26" class="icon"/>
        <heart-outline-icon :size="26" class="icon"/>
        <poll-icon :size="26" class="icon"/>
        <bookmark-outline-icon :size="26" class="icon"/>
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