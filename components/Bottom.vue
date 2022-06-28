<template>
  <div class="bt-layout">
    <nav class="level">
      <div class="level-item has-text-centered">
        <ul class="link is-info bt-left">
          <h1>工程计划</h1>
          <a class="link is-info">传输安全引擎</a>
          <a class="link is-info">通用组件库</a>
          <a class="link is-info">可用性测试</a>
          <a class="link is-info">开放知识库</a>
          <a class="link is-info">尖锐性设计</a>
          <a class="link is-info">全景式安全</a>
        </ul>
      </div>
      <div class="level-item has-text-centered">
        <ul class="link is-info bt-left">
          <h1>研究方向</h1>
          <a class="link is-info">传输安全</a>
          <a class="link is-info">金融科技</a>
          <a class="link is-info">操作系统</a>
          <a class="link is-info">开放参与</a>
          <a class="link is-info">社会科学</a>
        </ul>
      </div>
      <div class="level-item has-text-centered">
        <img src="/img/bottom-logo.png" style="width: 72px;margin-left: 130px;" />
      </div>
      <div class="level-item has-text-centered">
        <ul class="link is-info bt-right">
          <h1>加入我们</h1>
          <a class="link is-info">开放社区</a>
          <a class="link is-info">开放想法</a>
          <a class="link is-info">提案列表</a>
        </ul>
      </div>
      <div class="level-item has-text-centered">
          <ul class="link is-info bt-right">
            <h1>联系我们</h1>
            <a class="link is-info">jiangxue@jnun.org</a>
            <a class="link is-info">开放社区理事会</a>
            <a class="link is-info">江雪 <img src="/img/contact/opennesscommunity.png" style="width: 25px"/></a>
            <a class="link is-info">Jiangxue TEAM <img src="/img/contact/twitter.png" style="width: 25px"/> <img src="/img/contact/facebook.png" style="width: 25px"/> <img src="/img/contact/instagram.png" style="width: 25px"/></a>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "bottom"
}
</script>

<style scoped>
  img {
    margin-top: 10px;
  }
  nav {
    height: 556px;
    margin-top: 60px;
    width: 1554px;
    margin: 0 auto;
  }
  .bt-layout {
    width: 100%;
    position: absolute;
    left: 0;
    background: url(/img/bottom-background.png) 0% 0% / auto;
    background-repeat: no-repeat;
  }
  .link {
    display: block !important;
    font-size: 21px !important;
    color: #91A3B6 !important;
    line-height: 2.2;
  }
  .level>.level-item:not(.is-narrow) {
    display: block;
  }

  h1 {
    font-size: 30px;
    color: #3E5E7E;
    font-family: SourceHanSerifCN-Medium;
  }
  .bt-left {
    text-align: left;
  }
  .bt-right {
    text-align: right;
  }
</style>
