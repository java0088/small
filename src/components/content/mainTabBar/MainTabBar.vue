<template>
  <tab-bar>
    <tab-bar-item path="/home">
      <img slot="item-icon" src="../../../assets/img/tabbar/home.svg" alt />
      <img slot="item-icon-active" src="../../../assets/img/tabbar/home_active.svg" alt />
      <p slot="item-name">首页</p>
    </tab-bar-item>
    <tab-bar-item path="/category">
      <img slot="item-icon" src="../../../assets/img/tabbar/category.svg" alt />
      <img slot="item-icon-active" src="../../../assets/img/tabbar/category_active.svg" alt />
      <p slot="item-name">分类</p>
    </tab-bar-item>
    <tab-bar-item path="/cart">
      <img slot="item-icon" src="../../../assets/img/tabbar/shopcart.svg" alt />
      <img slot="item-icon-active" src="../../../assets/img/tabbar/shopcart_active.svg" alt />
      <p slot="item-name">购物车</p>
    </tab-bar-item>
    <tab-bar-item path="/profile">
      <img slot="item-icon" src="../../../assets/img/tabbar/profile.svg" alt />
      <img slot="item-icon-active" src="../../../assets/img/tabbar/profile_active.svg" alt />
      <p slot="item-name">我的</p>
    </tab-bar-item>
  </tab-bar>
</template>
<script>
import TabBar from '../../common/tabbar/TabBar.vue'
import TabBarItem from '../../common/tabbar/TabBarItem.vue'
export default {
  components: {
    TabBar,
    TabBarItem
  }
}
</script>
