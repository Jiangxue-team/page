<template>
  <div class="bt-layout">
    <div class="bt-layout_nav com-bottom">
      <div class="columns">
        <div class="column">
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
        <div class="column">
          <ul class="link is-info">
            <h1>研究方向</h1>
            <a class="link is-info">传输安全</a>
            <a class="link is-info">金融科技</a>
            <a class="link is-info">操作系统</a>
            <a class="link is-info">开放参与</a>
            <a class="link is-info">社会科学</a>
          </ul>
        </div>
        <div class="column" style="text-align: center !important;">
          <img src="/img/bottom-logo.png" style="width: 72px;" />
        </div>
        <div class="column" style="text-align: right;">
          <ul class="link is-info left-correct_title">
            <h1>加入我们</h1>
            <a class="link is-info left-correct">开放社区</a>
            <a class="link is-info left-correct">开放想法</a>
            <a class="link is-info left-correct">提案列表</a>
          </ul>
        </div>
        <div class="column">
          <ul class="link is-info" style="text-align: left">
            <h1>联系我们</h1>
            <a class="link is-info">jiangxue@jnun.org</a>
            <a class="link is-info">开放社区理事会</a>
            <a class="link is-info">江雪 <img src="/img/contact/opennesscommunity.png" style="width: 25px"/></a>
            <a class="link is-info">Jiangxue TEAM <img src="/img/contact/twitter.png" style="width: 25px"/> <img src="/img/contact/facebook.png" style="width: 25px"/> <img src="/img/contact/instagram.png" style="width: 25px"/></a>
          </ul>
        </div>
      </div>
      <div class="copyright">
        <p>版权 2019 江雪. 麻省理工学院许可证<span>Copyright © 2019 Jiangxue TEAM. MIT License</span></p>
      </div>
    </div>
    <div class="mob-bottom">
      <div class="mob-bottom_main">
        <img src="/img/bottom-logo_mob.png" />
        <ul class="link is-info" style="text-align: left">
          <a class="link is-info">江雪 <img src="/img/contact/opennesscommunity.png"></a>
          <a class="link is-info">Jiangxue TEAM <img src="/img/contact/twitter.png" /> <img src="/img/contact/facebook.png" /> <img src="/img/contact/instagram.png" /></a>
        </ul>
      </div>
      <div class="mob-bottom_copy"><p>版权 2019 江雪. 麻省理工学院许可证
        Copyright © 2019 Jiangxue TEAM. MIT License</p></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "bottom"
}
</script>

<style scoped>
  .copyright {
    font-size: 21px;
    color: #91A3B6 !important;
    position: relative;
    text-align: right;
  }
  .copyright p span {
    display: block;
  }
  .bt-layout_nav {
    height: 556px;
    width: 1554px;
    margin: 0 auto;
    margin-top: 252px;
    margin-bottom: 170px;
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
  h1 {
    font-size: 30px;
    color: #3E5E7E;
    font-family: SourceHanSerifCN-Medium;
  }
  .left-correct_title {
    margin-left: 40px;
    position: absolute;
    text-align: left;
  }
  @media screen and (max-width: 1534px) {
    .mob-bottom {
      display: block !important;
      width: 100%;
      padding: 2%;
      height: auto;
    }
    .mob-bottom img {
      width: 10%;
    }
    h1 {
      font-size: 15px;
    }
    .link {
      font-size: 15px !important;
    }
    .mob-bottom ul img {
      width: 16px;
    }
    .mob-bottom ul {
      margin-top: 4rem;
      margin-left: 1rem;
    }
    .mob-bottom_main {
      float: left;
      display: flex;
    }
    .mob-bottom_copy {
      display: inline-table;
      margin-top: 2rem;
      color: #91A3B6 !important;
      border-top: 1px solid rgba(145, 163, 182, 0.57);
      width: 100%;
      padding-top: 1.5rem;
    }
  }
  @media screen and (min-width: 1534px) {
    .mob-bottom {
      display: none;
    }
  }
</style>
