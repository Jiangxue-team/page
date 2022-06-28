<template>
  <div>
    <div class="ep-font">
      <span>浮云几何</span>
      <span>弹指太息</span>
      <p>核心提案</p>
    </div>
    <div class="ip-layout">
      <div style="background: url(/img/Important-proposal/1.png) 0% 0% / 236px 613px;width: 237px;height: 613px;">
        <p>匀音 <separator />
          传输安全引擎</p>
        <ul style="margin-left: 1em">
          <span><img src="/img/Important-proposal/label.png"> 基础安全实验室</span>
          <span><img src="/img/Important-proposal/label.png"> 电子对抗实验室</span>
        </ul>
      </div>
      <div style="background: url(/img/Important-proposal/2.png) 0% 0% / 236px 613px;width: 237px;height: 613px;">
        <p>琼楼 <separator />
          低代码构建框架</p>
        <ul style="margin-left: 1em">
          <span><img src="/img/Important-proposal/label.png"> 项目开发组</span>
          <span><img src="/img/Important-proposal/label.png"> 艺术设计与视觉传播组</span>
        </ul>
      </div>
      <div style="background: url(/img/Important-proposal/3.png) 0% 0% / 236px 613px;width: 237px;height: 613px;">
        <p>羬羊 <separator />
          自动化测试平台</p>
        <ul style="margin-left: 1em">
          <span><img src="/img/Important-proposal/label.png"> 基础安全实验室</span>
        </ul>
      </div>
      <div style="background: url(/img/Important-proposal/4.png) 0% 0% / 236px 613px;width: 237px;height: 613px;">
        <p>千曲 <separator />
          开放知识库</p>
        <ul style="margin-left: 1em">
          <span><img src="/img/Important-proposal/label.png"> 开放性研究组</span>
          <span><img src="/img/Important-proposal/label.png"> 社会与文化传播组</span>
        </ul>
      </div>
      <div style="background: url(/img/Important-proposal/5.png) 0% 0% / 236px 613px;width: 237px;height: 613px;">
        <p>蛟龙 <separator />
          尖锐性组件库</p>
        <ul style="margin-left: 1em">
          <span><img src="/img/Important-proposal/label.png"> 艺术设计与视觉传播组</span>
        </ul>
      </div>
      <div style="background: url(/img/Important-proposal/6.png) 0% 0% / 235px 613px;width: 237px;height: 613px;">
        <p>曲注 <separator />
          文字优化模型</p>
        <ul style="margin-left: 1em">
          <span><img src="/img/Important-proposal/label.png"> 人工智能实验室</span>
          <span><img src="/img/Important-proposal/label.png"> 智能计算实验室</span>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
import Separator from "~/static/separator";
export default {
  name: "ImportantProposal",
  components: {Separator}
}
</script>

<style scoped>
ul {
  display: flex;
}
.ip-layout div p {
  opacity: 0;
}
.ip-layout div span {
  opacity: 0;
}
.ip-layout div:hover p {
  opacity: 1;
}
.ip-layout div:hover span {
  opacity: 1;
}
span img {
  width: 15px !important;
  height: 15px !important;
}
.ip-layout p {
  margin-top: 72px;
  -ms-writing-mode: tb-lr;
  writing-mode: vertical-lr;
  -ms-writing-mode: tb-lr;
  writing-mode: tb-lr;
  margin-left: 3.7em;
  font-size: 25px;
  font-family: SourceHanSerifCN-Heavy;
  background: linear-gradient(180deg, #007FFF 0%, rgba(0, 0, 0, 0) 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  text-fill-color: transparent;
}
.ip-layout span {
  color: #5E5E5E;
  border-right: 2px solid #0082fd;
  -ms-writing-mode: tb-lr;
  writing-mode: vertical-lr;
  -ms-writing-mode: tb-lr;
  writing-mode: tb-lr;
}

.ip-layout div {
  opacity: 0.3;
}

.ip-layout div:hover {
  opacity: 1;
  cursor: pointer;
  transition: all 0.28s;
}
.ip-layout {
  display: flex;
  /* flex-direction: row; */
  /* flex-wrap: nowrap; */
  /* align-content: center; */
  /* justify-content: center; */
  /* align-items: center; */
  margin: 0 auto;
  padding: 0;
  margin-right: 9em;
}
img {
  width: 237px !important;
  height: 613px !important;
  margin: 0 !important;
}
.ep-font {
  margin-top: 72px;
  -ms-writing-mode: tb-lr;
  writing-mode: vertical-lr;
  -ms-writing-mode: tb-lr;
  writing-mode: tb-lr;
  /* width: 100%; */
  right: -45.5em;
}
.ep-font span {
  display: block;
  height: 85px;
  color: #5E5E5E;
  border-right: 2px solid #0082fd;
}
.ep-font p {
  font-size: 30px;
  font-family: 'SourceHanSerifCN-Medium';
  border-right: 2px solid #007FFF;
  height: 151px;
  color: #3E5E7E;
}
.ep-font p:after {
  content: '';
  width: 15px;
  height: 15px;
  display: inline-block;
  border-radius: 100%;
  border: 2.3px solid #007fff;
  position: relative;
  left: 10px;
  top: -11px;
}
div {
  margin: 0 auto;
  margin-bottom: 10px;
  position: relative;
}
img {
  width: 1553px;
}
</style>
