<template>
  <div class="m-nav">
    <ul class="nav">
      <li class="list">
        <nuxt-link to="/my">我的美团</nuxt-link>
        <dl>
          <dd>
            <nuxt-link to="/order">我的订单</nuxt-link>
          </dd>
          <dd>
            <nuxt-link to="/collect">我的收藏</nuxt-link>
          </dd>
          <dd>
            <nuxt-link to="/tickets">抵用券</nuxt-link>
          </dd>
          <dd>
            <nuxt-link to="/setting">账户设置</nuxt-link>
          </dd>
        </dl>
      </li>
      <li>
        <nuxt-link to="/app">手机App</nuxt-link>
      </li>
      <li class="list db">
        <nuxt-link to="/center">商家中心</nuxt-link>
        <dl>
          <dd>
            <nuxt-link to="/userCenter">登录商家中心</nuxt-link>
          </dd>
          <dd>
            <nuxt-link to="/coop">我想合作</nuxt-link>
          </dd>
          <dd>
            <nuxt-link to="/wap">手机免费开店</nuxt-link>
          </dd>
          <dd>
            <nuxt-link to="/kaipiao">商家申请开票</nuxt-link>
          </dd>
        </dl>
      </li>
      <li class="list site">
        <nuxt-link to="/site">网站导航</nuxt-link>
        <div class="subContainer">
          <dl class="hotel">
            <dt>酒店旅游</dt>
            <dd>自编标签1</dd>
            <dd>自编标签2</dd>
            <dd>自编标签3</dd>
            <dd>自编标签4</dd>
            <dd>自编标签5</dd>
            <dd>自编标签6</dd>
            <dd>自编标签7</dd>
            <dd>自编标签8</dd>
            <dd>自编标签9</dd>
            <dd>自编标签10</dd>
            <dd>自编标签11</dd>
            <dd>自编标签12</dd>
            <dd>自编标签13</dd>
            <dd>自编标签14</dd>
            <dd>自编标签15</dd>
            <dd>自编标签16</dd>
          </dl>
          <dl class="food">
            <dt>吃美食</dt>
            <dd>自编标签1</dd>
            <dd>自编标签2</dd>
            <dd>自编标签3</dd>
            <dd>自编标签4</dd>
            <dd>自编标签5</dd>
            <dd>自编标签6</dd>
            <dd>自编标签7</dd>
            <dd>自编标签8</dd>
            <dd>自编标签9</dd>
          </dl>
          <dl class="movie">
            <dt>看电影</dt>
            <dd>看电影1</dd>
            <dd>看电影2</dd>
            <dd>看电影3</dd>
            <dd>看电影4</dd>
            <dd>看电影5</dd>
            <dd>看电影6</dd>
            <dd>看电影7</dd>
            <dd>看电影8</dd>
          </dl>
          <dl class="app">
            <dt>看电影</dt>
            <dd>
              <a href="#">
                <img
                  class="appicon"
                  src="//s0.meituan.net/bs/fe-web-meituan/e5eeaef/img/appicons/meituan.png"
                  title="美团app"
                  alt="美团app">
              </a>
            </dd>
            <dd>
              <a href="#">
                <img
                  class="appicon"
                  src="//s0.meituan.net/bs/fe-web-meituan/e5eeaef/img/appicons/meituan.png"
                  title="美团app"
                  alt="美团app">
              </a>
            </dd>
            <dd>
              <a href="#">
                <img
                  class="appicon"
                  src="//s0.meituan.net/bs/fe-web-meituan/e5eeaef/img/appicons/meituan.png"
                  title="美团app"
                  alt="美团app">
              </a>
            </dd>
            <dd>
              <a href="#">
                <img
                  class="appicon"
                  src="//s0.meituan.net/bs/fe-web-meituan/e5eeaef/img/appicons/meituan.png"
                  title="美团app"
                  alt="美团app">
              </a>
            </dd>
            <dd>
              <a href="#">
                <img
                  class="appicon"
                  src="//s0.meituan.net/bs/fe-web-meituan/e5eeaef/img/appicons/meituan.png"
                  title="美团app"
                  alt="美团app">
              </a>
            </dd>
          </dl>
        </div>
      </li>
    </ul>
  </div>
</template>

<script>
  export default {
    name: "Nav"
  }
</script>

<style>

</style>
