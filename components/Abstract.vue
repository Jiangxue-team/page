<template>
  <div>
    <div>
      <div class="layout title">
        <h1>应对永无止境的安全威胁</h1>
        <span>Tackle never-ending security threats</span>
        <p>江雪（Jiangxue,team）是一支由非盈利组织联合现在所驱动的综合性开放性研究团队，以互联网基础协议的标准制定为驱动，通过计算机科学和应用技术为基础进行创新</p>
        <logo-ui />
        <img src="/img/news-background.png">
      </div>
    </div>
  </div>
</template>

<script>
import LogoUi from "~/static/logo-ui";

export default {
  name: "Abstract",
  components: {
    LogoUi,
  }
}
</script>

<style scoped>
  img {
    position: absolute;
    left: 0;
    margin-top: -4em;
    z-index: -10;
  }
  .title {
    text-align: -webkit-center;
    margin-top: 61px;
    width: 100%;
  }
  p span {
    width: 767px;
  }
  .title h1 {
    color: #3E5E7E;
    font-size: 24px;
    font-family: 'SourceHanSerifCN-SemiBold';
  }
  .title span {
    color: #DFDFDF;
    font-family: 'SourceHanSerifCN-SemiBold';
    font-size: 24px;
    position: relative;
    top: -23px;
    margin-bottom: 22px;
  }
  .title p {
    font-size: 15px;
    width: 767px;
    color: #8A8A8A;
    font-family: 'SourceHanSerifCN-Regular';
    font-weight: 100;
    margin-bottom: 42px;
  }
</style>
