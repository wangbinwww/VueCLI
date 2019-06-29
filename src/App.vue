<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link>|
      <router-link to="/about">About</router-link>
      <div class="title">Hello 如何处理css相关内容</div>
      <button class="btn_enter">进入课程</button>
    </div>
    <router-view />
  </div>
</template>

<style lang="less">
//lang="less"样式预处理

//less处理,先安装less 用于全局颜色定义
//可提取到颜色预处理文件colors.less
//@primary-color: gold;

//引入颜色less配置
@import "./colors.less";

.title {
  color: @primary-color;
}
.btn_enter {
  color: @primary-color;
}
</style>
