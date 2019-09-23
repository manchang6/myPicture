<template>
  <div>
    <home-swiper></home-swiper>
    <p class="text">哈哈</p>
    <p class="text1">哈哈</p>
    <p class="text1 ignore">哈哈</p>
  </div>
</template>
<script>
import HomeSwiper from './components/swiper'
export default {
  name: 'Home',
  components: {HomeSwiper: HomeSwiper}
}
</script>
<style lang="scss" scoped>
  .text{
    font-size: 40px;
  }
  .ignore{
    font-size:40px;
  }
</style>
