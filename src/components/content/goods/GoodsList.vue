<template>
  <div class="goods">
    <goods-list-item v-for="(item, index) in goods" :key="index" :goods-item="item" />
  </div>
</template>
<script>
import GoodsListItem from './GoodsListItem.vue'
export default {
  props: {
    goods: {
      type: Array,
      default() {
        return []
      }
    }
  },
  components: {
    GoodsListItem
  }
}
</script>
<style lang="less" scoped>
.goods {
  display: flex;
  flex-wrap: wrap;
  background-color: #fff;
  justify-content: space-around;
}
</style>
