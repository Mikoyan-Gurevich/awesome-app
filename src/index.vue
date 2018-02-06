<template>
  <div class="wrapper">
    <image :src="logo" class="logo"></image>
    <text class="ownerInfo">Joshi bhaiya is the best</text>
    <text class="message">Now, let's use Vue.js to build your Weex app.</text>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        logo: 'https://gw.alicdn.com/tfs/TB1yopEdgoQMeJjy1XaXXcSsFXa-640-302.png',
      }
    }
  }
</script>

<style scoped>
  .wrapper {
    justify-content: center;
    align-items: center;
  }
  .logo {
    width: 424px;
    height: 200px;
  }
  .ownerInfo {
    margin-top: 70px;
    font-size: 30px;
    color: #41B883;
  }
  .message {
    margin: 30px;
    font-size: 32px;
    color: #727272;
  }
</style>
