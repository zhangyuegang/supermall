<template>
  <div id="tab-bar">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: "tabBar",
  data() {
    return {};
  },
};
</script>

<style lang='scss' scoped>
#tab-bar {
  display: flex;
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: #f5f5f5;
  box-shadow: 0 -3px 1px rgba(0, 0, 0, 0.05);
}
</style>