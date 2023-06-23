<template>
    <div><h2>Who to follow</h2>
      <RecommendedAccount></RecommendedAccount>
      <RecommendedAccount></RecommendedAccount>
      <RecommendedAccount></RecommendedAccount>
    </div>
</template>
<script>

import RecommendedAccount from './RecommendedAccount.vue';

export default{
  components: {
        RecommendedAccount
    }
}

</script>
