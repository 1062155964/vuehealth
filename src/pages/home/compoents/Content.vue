<template>
  <div>
    <ul>
      <li class="list-body">
        <div class="content">
          <span class="iconfont content-icon icon-sleep">&#xe62a;</span>
          <span class="content-menu ">睡眠监控</span>
          <span class="iconfont content-nav">&#xe6a1;</span>
        </div>
      </li>
      <li class="list-body">
        <div class="content">
          <span class="iconfont content-icon icon-hrate">&#xe6e4;</span>
          <span class="content-menu">心率检测</span>
          <span class="iconfont content-nav">&#xe6a1;</span>
        </div>
      </li>
      <li class="list-body">
        <div class="content">
          <span class="iconfont content-icon icon-dwater">&#xe600;</span>
          <span class="content-menu">喝水提醒</span>
          <span class="iconfont content-nav">&#xe6a1;</span>
        </div>
      </li>
      <li class="list-body">
        <div class="content">
          <span class="iconfont content-icon icon-sport">&#xe614;</span>
          <span class="content-menu">运动报告</span>
          <span class="iconfont content-nav">&#xe6a1;</span>
        </div>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Homecontent'
}
</script>

<style lang="stylus" scoped>
  .list-body
    overflow :hidden
    width : 100%
    font-size :.35rem
    line-height :.9rem
    .content
      border :1px solid #eee
      .icon-sleep
        font-size: .4rem
        color: rgb(14,163,255)
      .icon-hrate
        font-size: .4rem
        color: rgb(250,93,58)
      .icon-dwater
        font-size: .4rem
        color: rgb(45,198,255)
      .icon-sport
        font-size: .4rem
        color: rgb(14,163,255)
      .content-icon
        margin-left: .2rem
        float :left
      .content-menu
        margin-left : .4rem
      .content-nav
        float: right
        margin-right: .4rem
</style>
