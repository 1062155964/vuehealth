<template>
  <div class="header">
    <div class="header-body">
      <div class="header-body-content">
        今日步数<br><br>
        <span class="content-foot">0</span>
        <span class="content-bage">步</span>
        <br>
        <button class="content-button">去跑步</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
  .header
   position :relative
   width :100%
   padding-bottom :80%
   background-color :rgb(14,163,255)
   color :rgb(206,237,255)
   .header-body
    position :absolute
    font-size :.4rem
    top :50%
    left :50%
    transform :translate(-50%,-50%)
    text-align : center
    .content-foot
      margin-left: .4rem
      font-size: 1rem
      color :#fff
    .content-bage
      font-size :.2rem
    .content-button
      margin-top: .6rem
      color: #fff
      background :rgb(38,173,255)
      border :1px solid rgb(83,180,255)
      border-radius :  .3rem
      padding: 0 .3rem
</style>
