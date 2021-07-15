<template>
  <div class="bottom-bar">
    <div class="bar-item bar-left">
      <div>
        <i class="icon service"> </i>
        <span class="text">客服</span>
      </div>
      <div>
        <i class="icon service"> </i>
        <span class="text">店铺</span>
      </div>
      <div>
        <i class="icon service"> </i>
        <span class="text">收藏</span>
      </div>
    </div>
    <div class="bar-item bar-right">
      <div class="cart">加入购物车</div>
      <div class="buy">购买</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "DetailBottomBar",
};
</script>


<style scoped>
.bottom-bar {
  height: 49px;
  background-color: #fff;
  position: relative;
  display: flex;
  text-align: center;
}
.bar-item {
  flex: 1;
  display: flex;
}
.bar-item > div {
  flex: 1;
}
.cart,
.buy,
.text {
  line-height: 49px;
  font-size: 13px;
  color: black;
}
.cart {
  background-color: rgb(219, 219, 40);
  font-style: 16px;
}
.buy {
  background-color: rgb(219, 94, 115);
  font-style: 16px;

  color: #fff;
}
</style>