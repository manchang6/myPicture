<template>
<div class="swiper">
  <mt-swipe :auto="4000">
    <mt-swipe-item><img class="img" src='../../assets/banner1.png'/></mt-swipe-item>
    <mt-swipe-item><img class="img" src='../../assets/banner2.png'/></mt-swipe-item>
    <mt-swipe-item><img class="img" src='../../assets/banner3.png'/></mt-swipe-item>
    <mt-swipe-item><img class="img" src='../../assets/banner4.png'/></mt-swipe-item>
    <mt-swipe-item><img class="img" src='../../assets/banner5.png'/></mt-swipe-item>
    <mt-swipe-item><img class="img" src='../../assets/banner6.png'/></mt-swipe-item>
  </mt-swipe>
</div>
</template>
<script>
export default {
  name: 'homeSwiper',
  methods: {}
}
</script>
<style>
.swiper {
  width:100%;
  height: 640px;
}
.img{
  width:375px;
}
</style>
