<template>
  <div id="app" class="wrapper">
    <router-view/>
    <main-tab-bar/>
  </div>
</template>

<script>

import MainTabBar from "./components/content/MainTabBar";

export default {
  name: 'App',
  components: {
    MainTabBar
  }
}
</script>

<style>
  @import "assets/css/base.css";
</style>
