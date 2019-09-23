<template>
<div class="swiper">
  <mt-swipe :auto="4000">
    <mt-swipe-item v-for="item in swiperData" :key="item">
      <img class="img" :src='item'/>
    </mt-swipe-item>
  </mt-swipe>
</div>
</template>
<script>
export default {
  name: 'homeSwiper',
  data(){
    return {
      swiperData: [
        require('@/assets/images/banner1.png'),
        require('@/assets/images/banner2.png'),
        require('@/assets/images/banner3.png'),
        require('@/assets/images/banner4.png'),
        require('@/assets/images/banner5.png'),
        require('@/assets/images/banner6.png'),
      ]
    }
  },
  methods: {}
}
</script>
<style lang="scss" scoped>
.swiper {
  width:100%;
  height: 200px;
}
.img{
  width: 100%;
}
</style>
