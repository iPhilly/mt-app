<template>
  <!--m:module-->
  <div class="m-geo">
    <i class="el-icon-location"/>
    <span>北京市</span>
    <nuxt-link
      class="changeCity"
      to="/changeCity">切换城市</nuxt-link>
    [香河 廊坊 天津]
  </div>
</template>

<script>

  import { Button } from 'element-ui'
  export default {
    name: "Geo"
  }
</script>

<style>

</style>
