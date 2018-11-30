<template>
  <div class="m-header">
    <el-row>
      <top-bar/>
    </el-row>
    <el-row>
      <el-col>
        <search-bar/>
      </el-col>
    </el-row>
  </div>
</template>

<script>

  import topBar from './topbar'
  import searchBar from './searchbar'
  export default {
    components: {
      searchBar,
      topBar
    }
  }
</script>

<style>
  @import "@/assets/css/public/header/index.scss";

</style>
