<template>
  <div id="app">
    <img src="./assets/logo.png">
    <!-- <router-view/> -->
    <div>
      <a style="font-size: 30px;" href="itms-services://?action=download-manifest&url=https://read-public-test.oss-cn-hangzhou.aliyuncs.com/manifest.plist">ipa下载地址</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
