<template>
  <tab-bar>
      <tab-bar-item path="/home" activeColor="deeppink">
        <img  src="../assets/img/tabbbar/home.svg" alt="" slot="item-icon">
        <img  src="../assets/img/tabbbar/home_active.svg" alt="" slot="item-icon-active">
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="category" activeColor="deeppink">
        <img src="../assets/img/tabbbar/category.svg" alt=""  slot="item-icon">
        <img src="../assets/img/tabbbar/category_active.svg" alt=""  slot="item-icon-active">
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path='cart' activeColor="deeppink">
        <img src="../assets/img/tabbbar/cart.svg" alt="" slot="item-icon">
        <img src="../assets/img/tabbbar/cart_active.svg" alt="" slot="item-icon-active">
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path='profile' activeColor="deeppink">
        <img src="../assets/img/tabbbar/profile.svg" alt="" slot="item-icon">
        <img src="../assets/img/tabbbar/profile_active.svg" alt="" slot="item-icon-active">
        <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar>
</template>

<script>
import TabBar from './tabbar/TabBar'
import TabBarItem from './tabbar/TabBarItem'

export default {
  name: 'MainTabBar',
  components: {
    TabBarItem,
    TabBar
  }
}
</script>

<style>

</style>