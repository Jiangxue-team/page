<template>
  <div class="default">
    <navigation />
    <nuxt />
    <bottom/>
  </div>
</template>

<script>
export default {
  name: "default"
}
</script>

<style>
@font-face {
  font-family: "SourceHanSerifCN-Bold";
  src: url("/font/SourceHanSerifCN-Bold.otf");
}
@font-face {
  font-family: "SourceHanSerifCN-Regular";
  src: url("/font/SourceHanSerifCN-Regular.otf");
}
@font-face {
  font-family: "SourceHanSerifCN-SemiBold";
  src: url("/font/SourceHanSerifCN-SemiBold.otf");
}
@font-face {
  font-family: "SourceHanSerifCN-Medium";
  src: url("/font/SourceHanSerifCN-Medium.otf");
}
@font-face {
  font-family: "SourceHanSerifCN-Heavy";
  src: url("/font/SourceHanSerifCN-Heavy.otf");
}
body {
  padding: 0;
  margin: 0;
  display: block;
  font-family: SourceHanSerifCN-Regular;
}
.default {
  margin-top: 1em;
  width: 1554px;
  margin: 0 auto;
}
</style>
