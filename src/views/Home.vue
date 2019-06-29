<template>
  <div class="home">
    <HelloWorld msg="欢迎使用Vue.js App" />
    <h1 class="title">less测试</h1>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
export default {
  name: "home",
  components: {
    HelloWorld
  }
};
</script>

<style lang="less">
.title {
  color: @primary-color;
  font-size: @normal-size;
}
.btn_enter {
  color: @primary-color;
}
</style>