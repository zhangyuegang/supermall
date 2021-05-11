<template>
  <div calss=''>
    <nav-bar>
      <div slot="center">购物车</div>
    </nav-bar>
  </div>
</template>

<script>
import NavBar from 'components/common/navbar/NavBar'

export default {
  name: 'Home',
  data() {
    return {
      
    }
  },
  components: {
    NavBar
  }
}
</script>

<style lang='scss' >
  .nav-bar{
    background-color: var(--color-tint);
  }
</style>