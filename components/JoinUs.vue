<template>
  <div class="ep-font">
    <div>
      <span>因为热爱</span>
      <span>方可无惧</span>
      <p>加入我们</p>
      <span style="height: 180px;">选择或发布你的想法</span>
      <span>共同完成</span>
    </div>
  </div>
</template>

<script>
export default {
  name: "JoinUs"
}
</script>

<style scoped>
.ep-font {
  margin-top: 72px;
  writing-mode: vertical-lr;/*从左向右 从右向左是 writing-mode: vertical-rl;*/
  writing-mode: tb-lr;/*IE浏览器的从左向右 从右向左是 writing-mode: tb-rl；*/
  width: 100%;
}
span {
  display: block;
  height: 85px;
  color: #5E5E5E;
  border-right: 2px solid #0082fd;
}
p {
  font-size: 30px;
  font-family: 'SourceHanSerifCN-Medium';
  border-right: 2px solid #007FFF;
  height: 151px;
  color: #3E5E7E;
}
p:after {
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
  display: inline-grid;
  margin-bottom: 10px;
}
img {
  width: 1553px;
}
</style>
