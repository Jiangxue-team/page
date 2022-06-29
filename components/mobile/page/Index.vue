<template>
  <div class="mob-index">
    <Streamer />
    <div class="mob-layout_abstract mob-layout_abstract_back">
      <p class="mob-layout_abstract title">应对永无止境的安全威胁</p>
      <p class="mob-layout_abstract en">Tackle never-ending security threats</p>
      <p class="mob-layout_abstract desc">江雪是一支非营利性多边领域研究团队，由计算机科学和应用为驱动</p>
      <p class="mob-layout_abstract desc">以互联网基础协议的标准制定为驱动，通过计算机科学和应用技术为基础进行创新</p>
      <img src="/img/news-background.png">
    </div>
    <div class="mob-title">
      <p>新闻动态</p>
      <span>News & Trends</span>
    </div>
    <div class="mob-layout_news">
      <news />
    </div>
    <div class="mob-title">
      <p>核心提案</p>
      <span>Core proposal</span>
    </div>
    <div class="engineering">
      <important-proposal />
    </div>
    <div class="mob-title">
      <p>团队概述</p>
      <span>Summary of team</span>
    </div>
    <div class="mob-overview">
      <center><overview /></center>
    </div>
  </div>
</template>

<script>
import Streamer from "~/components/swiperjs/Streamer";
import News from "~/components/swiperjs/News";
import Overview from "~/components/swiperjs/Overview";
export default {
  name: "index",
  components: {
    Overview,
    News,
    Streamer,
    }
}
</script>

<style>
  @media screen and (min-width: 1534px) {
    .mob-index {
      display: none;
    }
  }
  @media screen and (max-width: 1534px) {
    .navbar-burger {
      height: 7.25rem !important;
    }
    .mob-layout_abstract {
      padding: 2em;
      text-align: center;
    }
    .mob-layout_abstract img {
      position: absolute;
      left: 0;
      margin-top: -4em;
      z-index: -10;
    }
    .mob-layout_abstract .title {
      color: #3E5E7E;
      font-size: 19px;
      margin: 0;
      padding: 0;
    }
    .mob-layout_abstract .en {
      color: #DFDFDF;
      margin: 0;
      padding: 0;
    }
    .mob-layout_abstract .desc {
      color: #8A8A8A;
      margin: 0;
      padding: 0;
      font-size: 15px;
      margin-top: 1em;
    }
    .mob-title {
      margin-top: 3em;
      margin-bottom: 3em;
      text-align: center;
      font-family: SourceHanSerifCN-Bold;
    }
    .mob-title span {
      font-size: 14px;
    }
    .mob-layout_news div {
      width: 100% !important;
      justify-content: space-around;
      flex-direction: column;
      /* display: flow-root; */
      height: auto !important;
      margin: 0;
      left: 0;
      right: 0;
      height: auto !important;
      margin-right: 0 !important;
      display: contents !important;
    }
  }
</style>
