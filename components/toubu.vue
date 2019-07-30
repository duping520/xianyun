<template>
  <div class="toubu">
    <el-row type="flex" class="banxin" justify="space-between">
      <!-- logo -->
      <div class="logo">
        <nuxt-link to="/">
          <img src="http://157.122.54.189:9093/images/logo.jpg" alt />
        </nuxt-link>
      </div>
      <!-- 导航栏 -->
      <el-row type="flex" class="daohang">
        <nuxt-link to="/">首页</nuxt-link>
        <nuxt-link to="/post">旅行攻略</nuxt-link>
        <nuxt-link to="/hotel">酒店</nuxt-link>
        <nuxt-link to="/air">国内机票</nuxt-link>
      </el-row>
      <el-row class="denglu" type="flex">
        <nuxt-link to="/user/login">登录/注册</nuxt-link>
      </el-row>
    </el-row>
  </div>
</template>

<script>
export default {};
</script>

<style scoped lang='less'>
.toubu {
  height: 60px;
  line-height: 60px;
  border-bottom: 1px solid red;
}
.banxin {
  width: 1000px;
  margin: 0 auto;
}
.logo {
  width: 156px;
  //   padding-top: 8px;
  img {
    display: block;
    width: 100%;
    margin-top: 6px;
  }
}
.daohang {
  flex: 1;
  margin-left: 10px;
  a {
    padding: 0 20px;
    display: block;
    height: 60px;
    line-height: 60px;
    margin-left: 30px;
    box-sizing: border-box;
    &:hover {
      color: #409eff;
      border-bottom: 5px solid #409eff;
    }
  }
}
.denglu {
  a {
    font-size: 14px;
    &:hover {
      color: #409eff;
      border-bottom: 1px solid #409eff;
    }
  }
}
.nuxt-link-exact-active {
  background: #409eff;
  color: #fff;

  &:hover {
    color: #fff;
  }
}
</style>
