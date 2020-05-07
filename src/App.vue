<template>
  <div id="app">
    <!-- 顶部栏 -->
     <mt-header :title="this.$route.name">
      <router-link to="/" slot="left">
        <mt-button icon="back">返回</mt-button>
      </router-link>
      <mt-button icon="more" slot="right"></mt-button>
    </mt-header>

    <!-- 底部栏 -->
    <router-view></router-view>
  </div>
</template>

<style>
* {
  padding: 0;
  margin: 0;
}
</style>
