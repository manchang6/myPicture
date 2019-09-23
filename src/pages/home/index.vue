<template>
  <div class="module_home">
    <div class="mark_bg">
      <ul class="menu_box">
        <li class="menu_list" v-for="item in menuData" :key="item.id">
          <router-link class="item_link" :to="item.link">
            <span class="en_name">{{item.mes}}</span>
            <br />
            <span class="zh_name">{{item.name}}</span>
          </router-link>
        </li>
      </ul>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Home',
  components: {},
  data(){
    return {
      menuData: [
        {
          name: '他, 她',
          mes: 'PICTURE CENTER',
          id: 1,
          link: 'http://www.baidu.com'
        },
        {
          name: '这里有诗和远方',
          mes: 'ALBUM CENTER',
          id: 2,
          link: 'http://www.baidu.com'
        },
        {
          name: '看我么',
          mes: 'PERSONAL CENTER',
          id: 3,
          link: 'http://www.baidu.com'
        }
      ]
    }
  }
}
</script>
<style lang="scss" scoped>
  .module_home{
    width:100vw;
    height:100vh;
    position: relative;
    // background:url('~@/assets/images/home_bg.gif')center center no-repeat;
    .mark_bg{
      width:100%;
      height:100%;
      position: absolute;
      left:0;
      top:0;
      right:0;
      bottom:0;
      background:rgba(0,0,0,0.8);
    }
    .menu_box{
      width: 100%;
      height:auto;
      padding:var(--screenGap);

    }
    .menu_list{
      margin-bottom:24px;
      line-height:42px;
      .item_link{
        color:#ffffff;
      }
      .en_name{
        font-size:40px;
        font-weight: bold;
      }
      .zh_name{
        font-size:24px;
      }
    }
  }
</style>
