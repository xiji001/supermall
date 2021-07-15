<template>
  <div>
    <div class="content">用户评价数据</div>
  </div>
</template>

<script>
export default {
  name: "DetailCommentInfo",
  props: {
    commentInfo: {
      type: Object,
      default: {
        return: {},
      },
    },
  },
};
</script>

<style scoped>
.content {
  color: pink;
}
</style>