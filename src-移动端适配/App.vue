<template>
  <div>
    <h1>App 组件</h1>
    <p>测试适配</p>
    <div class="box">
      box
    </div>
  </div>
</template>

<script>
  export default {

  }
</script>

<style lang="stylus" rel="stylesheet/stylus">
  @import "./common/stylus/mixins.styl"

  p
    width 375px
    height 100px
    background green
  .box
    width 640px
    height 64px
    background red

</style>
