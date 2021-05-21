<template>
  <div class="header">
    <div class="header-left">
        <div class="iconfont icon-back">&#xe624;</div>
    </div>
    <div class="header-input">
        <span class="iconfont">&#xe632;</span>
        输入城市/景点/游玩主题
    </div>
    <div class="header-right">
        城市
        <span class="iconfont arrow-icon">&#xe64a;</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
@import '~styles/varibles.styl'
.header
  height: .86rem
  display: flex
  background: $bgColor;
  line-height: .86rem
  color: #fff
.header-left
  width: .64rem
  .icon-back
    text-align: center
    font-size: .4rem
.header-input
  flex: 1
  height: .62rem
  margin-top: .12rem
  margin-left: .2rem
  background: #fff
  border-radius: .1rem
  line-height: .62rem
  color: #ccc
  padding-left: .2rem
.header-right
  width: 1.24rem
  text-align: center
  .arrow-icon
    font-size: .2rem
    margin-left: -.04rem
</style>
