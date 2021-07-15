<template>
  <div>
    <nav-bar class="cart-nav">
      <div slot="center">购物车</div>
    </nav-bar>
    <!-- <cart-list></cart-list> -->
  </div>
</template>

<script>
// import cartList from "./childComps/cartList.vue";

import NavBar from "components/common/navbar/NavBar";

export default {
  components: {
    NavBar,
    // cartList
  },
  name: "cart",
};
</script>

<style scoped>
.cart-nav {
  background-color: var(--color-tint);
  color: #fff;
}
</style>