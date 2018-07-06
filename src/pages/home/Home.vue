<template>
  <div>
    <home-header></home-header>
    <home-content></home-content>
    <home-paging></home-paging>
  </div>
</template>

<script>
import HomeHeader from './compoents/Header'
import HomeContent from './compoents/Content'
import HomePaging from './compoents/Paging'
export default {
  name: 'Home',
  components: {
    HomeHeader,
    HomeContent,
    HomePaging
  }
}
</script>

<style>

</style>
