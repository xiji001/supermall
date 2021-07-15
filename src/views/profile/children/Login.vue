<template>
  <div class="login">
    <div class="user-pic">
      <img src="~assets/img/profile/avatar.svg" alt="" />
    </div>
    <div class="user-info">
      <p>登录/注册</p>
      <div class="phone-num">
        <img src="~assets/img/profile/phone.svg" alt="" />
        <p>暂未绑定手机号</p>
      </div>
    </div>
    <i class="more">></i>
  </div>
</template>

<script>
export default {
  name: "Login",
  data() {
    return {};
  },
};
</script>

<style scoped>
.login {
  position: relative;
  display: flex;
  align-items: center;
  width: 100%;
  height: 90px;
  padding: 0 20px;
  background-color: #ff8198;
}

.user-pic {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 60px;
  height: 60px;
  border-radius: 50%;
  background-color: #fff;
}

.user-pic img {
  width: 65px;
}

.user-info {
  margin-left: 20px;
  color: #fff;
}

.user-info .phone-num {
  font-size: 14px;
  display: flex;
  align-items: center;
  margin-top: 8px;
}
.phone-num img {
  width: 15px;
}

.more {
  color: #fff;
  position: absolute;
  right: 10px;
  width: 20px;
  height: 20px;
}
</style>
