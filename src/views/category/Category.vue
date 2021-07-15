<template>
  <div>
    <nav-bar class="cate-nav"><div slot="center">商品分类</div></nav-bar>
    <tab-control
      :titles="['流行', '新款', '精选']"
      class="tab-control"
    ></tab-control>
    <div class="left">
      <span>男装</span>
      <span>女装</span>
      <span>童装</span>
      <span>流行</span>
      <span>内衣</span>
      <span>新款</span>
      <span>男装</span>
    </div>
  </div>
</template>

<script>
import NavBar from "components/common/navbar/NavBar";

import TabControl from "components/content/tabControl/TabControl";

export default {
  name: "category",
  components: {
    NavBar,
    TabControl,
  },
  data() {
    return {};
  },
};
</script>

<style scoped>
.cate-nav {
  background-color: var(--color-tint);
  color: #fff;
}
.tab-control {
  margin-left: 25%;
}
.left {
  display: flex;
  flex-direction: column;
  text-align: center;
  position: relative;
  bottom: 40px;
  width: 25%;
  height: calc(100vh - 44px - 49px);
  background-color: #ececec;
}
.left span {
  flex: 1;
  margin-top: 30px;
}
</style>