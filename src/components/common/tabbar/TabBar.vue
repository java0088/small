<template>
  <div id="tab-bar">
    <slot></slot>
  </div>
</template>
<script>

export default {

}
</script>
<style scoped>
#tab-bar {
  position: fixed;
  z-index: 9999;
  left: 0;
  right: 0;
  bottom: 0;
  display: flex;
  background-color: #f5f5f5;
  box-shadow: 0 -3px 1px rgba(100, 100, 100, 0.3);
}
</style>
