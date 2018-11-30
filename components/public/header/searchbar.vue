<template>
  <div class="search-panel">
    <el-row class="m-header-searchbar">
      <el-col
        :span="3"
        class="left">
        <img
          class="appicon"
          src="//s0.meituan.net/bs/fe-web-meituan/e5eeaef/img/appicons/meituan.png"
          title="美团app"
          alt="美团app">
      </el-col>
      <el-col
        :span="15"
        class="center">
        <div class="wrapper">
          <el-input
            v-model="searchText"
            placeholder="搜索商家或地点"
            @focus="_focus"
            @blur="_blur"/>
          <el-button
            type="primary"
            icon="el-icon-search"/>
          <dl
            v-show="isShowHotplace"
            class="hotPlace"
            style="display: none;">
            <dt>热门搜索</dt>
            <dd>火锅</dd>
            <dd>小龙虾</dd>
            <dd>烧烤</dd>
          </dl>
          <dl
            v-show="isShowSearchList"
            class="searchList"
            style="display: none;">
            <dd>火锅</dd>
            <dd>烧烤</dd>
          </dl>
        </div>
        <p class="suggest">
          <a href="#">故宫博物院</a>
          <a href="#">故宫博物院</a>
          <a href="#">故宫博物院</a>
          <a href="#">故宫博物院</a>
          <a href="#">故宫博物院</a>
        </p>
        <ul class="nav">
          <li>
            <nuxt-link to="takeout">美团外卖</nuxt-link>
          </li>
          <li>
            <nuxt-link to="movie">猫眼电影</nuxt-link>
          </li>
          <li>
            <nuxt-link to="hotel">美团酒店</nuxt-link>
          </li>
          <li>
            <nuxt-link to="apartment">民宿/公寓</nuxt-link>
          </li>
          <li>
            <nuxt-link to="business">商家入住</nuxt-link>
          </li>
        </ul>
      </el-col>
      <el-col
        :span="6"
        class="right">
        <ul class="security">
          <li><i class="refund">
            <p class="txt">随时退1</p>
          </i></li>
          <li><i class="single">
            <p class="txt">随时退2</p>
          </i></li>
          <li><i class="overdue">
            <p class="txt">随时退3</p>
          </i></li>
        </ul>
      </el-col>
    </el-row>
  </div>
</template>

<script>

  export default {
    data() {
      return {
        isFocus: false,
        searchText: ''
      }
    },
    computed: {
      isShowSearchList: function() {
        return this.isFocus && this.searchText
      },
      isShowHotplace: function() {
        return this.isFocus && !this.searchText
      }
    },
    methods: {
      _focus:function(){
        this.isFocus = true
      },
      _blur:function(){
        let self = this;
        setTimeout(()=>{
          self.isFocus = false
        },200) // 延时失去焦点,否则无法点中下面的选项
      }
    }
  }
</script>

<style>

</style>
