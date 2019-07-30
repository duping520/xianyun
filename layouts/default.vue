<template>
  <div>
    <!-- 头部组件 -->
    <Toubu />
    <!-- 占位符   新写法  nuxt -->
    <nuxt />
  </div>
</template>

<script>
import Toubu from "@/components/toubu.vue";
export default {
  components: {
    Toubu
  }
};
</script>

<style lang="less">
* {
  margin: 0;
  padding: 0;
}
ul,
li,
ol {
  list-style: none;
}
a {
  text-decoration: none;
  color: inherit;
}
em,
i {
  font-style: normal;
}
</style>

