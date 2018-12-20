<template>
  <div class="header ">
    <div>
      <div class="iconfont header_icon_phone">&#xe686;
        <span>+180 0245 3925</span>
      </div>
      <div class="iconfont header_icon_email">&#xe667;
        <span>info@yourdomain.com</span>
      </div>
      <div class="iconfont header_icon_login">&#xe6f0;
        <span>登录</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style lang="stylus" scoped>
  @import '../assets/styl/varibles.styl'
  .header {
    width 70%;
    height 40px;
    margin 0 auto
    .header_icon_phone{
      color $homeHeadColor
      line-height 40px
      font-size 13px
      float left
    }
    .header_icon_email{
      color $homeHeadColor
      line-height 40px
      font-size 13px
      float left
      margin-left 1rem
    }
    .header_icon_login{
      color $homeHeadColor
      line-height 40px
      font-size 13px
      float right
      margin-right 3rem
    }
    .header_icon_login:hover{
      color #25a4bb
      cursor: pointer
    }
  }
</style>
