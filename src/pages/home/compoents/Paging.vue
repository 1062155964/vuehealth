<template>
  <div class="paging">
    <div class="paging-postion">
      <div class="page">
        <div class="page-icon">
          <span class="iconfont icon-home-active">&#xe69e;</span>
          <div class="page-content-active">主页</div>
        </div>
      </div>
      <div class="page">
        <div class="page-icon">
          <span class="iconfont icon-rank">&#xe734;</span>
          <div class="page-content">排行</div>
        </div>
      </div>
      <div class="page">
        <div class="page-icon">
          <span class="iconfont icon-user">&#xe602;</span>
          <div class="page-content">我</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePaging'
}
</script>

<style lang="stylus" scoped>
  .paging
    position :absolute
    height :0
    padding-bottom :17.5%
    width :100%
    border : 1px solid #eee
    bottom :0px
    .paging-postion
      display :flex
      .page
        position :relative
        flex:1
        padding-bottom :17.5%
        text-align :center
        .page-icon
          position :absolute
          top:10%
          left: 50%
          transform :translatex(-50%)
          .icon-home-active
            font-size :.8rem
            color :rgb(14,163,255)
          .page-content-active
            margin-top: .05rem
            color :rgb(14,163,255)
          .icon-rank
            font-size :.8rem
          .icon-user
            font-size :.8rem
          .page-content
            margin-top: .05rem
</style>
