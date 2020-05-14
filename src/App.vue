<template>
  <div id="app">
    <router-view></router-view>
    <tab-bar></tab-bar>
  </div>
</template>

<script>
import TabBar from 'components/content/TabBar'
export default {
  name:"app",
  components: {
    TabBar
  }
}
</script>

<style>
  @import url('~assets/css/reset.css');
</style>
