<template>
  <div class="home-header">
    <div class="logo"></div>
    <!-- <div class="person iconfont">&#xe64f;</div>
    <router-link to="/search" tag="div" class="search"><span class="search-icon iconfont">&#xe659;</span>专辑/歌单/歌名</router-link> -->
  </div>
</template>

<script type="text/javascript">
export default {
  name: 'Header'
}
</script>

<style lang="stylus" rel="stylesheet" scoped>
  @import '~common/styles/variable.styl'
  .home-header
    position: absolute
    top: 0
    left: 0
    width: 100%
    height: .5rem
    line-height: .5rem
    background: $color-background-them
  .logo
    width: 1.3rem
    height: .5rem
    margin: 0 auto
    background-image: url('~common/image/logo.png')
    background-size: auto .25rem
    background-repeat: no-repeat
    background-position: center
  .search
    height: .26rem
    margin-top: .13rem
    margin-left: 1.6rem
    margin-right: .4rem
    background: $color-background-d
    border-radius: .13rem
    line-height: .26rem
    padding: 0 0 0 .06rem
    font-size: $font-size-small-s
    color: $color-text-d
    .iconfont
      font-size: $font-size-small
      padding-right: .02rem
  .person
    float: right
    margin-right: .1rem
    color: $color-theme
</style>
