<template>
  <swiper class="swiper" :options="swiperOption">
    <swiper-slide style="background: url('img/streamer/1.png');background-size: auto 455px;">
      <div class="swiper-layout">
        <p>天地无尘，山河有影</p>
        <span>2022 OPENNESS COMMUNITY (OCO) 项目启动，助力江雪基础服务落地与研究进程。</span>
      </div>
    </swiper-slide>
    <swiper-slide style="background: red">Slide 10</swiper-slide>
    <swiper-slide style="background: red">Slide 10</swiper-slide>
    <swiper-slide style="background: red">Slide 10</swiper-slide>
    <swiper-slide style="background: red">Slide 10</swiper-slide>
    <div class="swiper-pagination" slot="pagination"></div>
    <div class="swiper-button-prev" slot="button-prev"></div>
    <div class="swiper-button-next" slot="button-next"></div>
  </swiper>
</template>

<script>
import { Swiper, SwiperSlide } from 'vue-awesome-swiper'
import 'static/css/swiper-bundle.min.css'

export default {
  name: "Streamer",
  components: {
    Swiper,
    SwiperSlide
  },
  data() {
    return {
      swiperOption: {
        slidesPerView: 1,
        spaceBetween: 30,
        loop: true,
        pagination: {
          el: '.swiper-pagination',
          clickable: true
        },
        navigation: {
          nextEl: '.swiper-button-next',
          prevEl: '.swiper-button-prev'
        }
      }
    }
  }
}
</script>

<style scoped>
.swiper-layout {
  margin-top: 190px;
  height: 74px;
  margin-left: 34px;
  width: 423px;
  color: white;
}

.swiper-layout p {
  font-family: SourceHanSerifCN-Bold;
  font-size: 20px;
}
.swiper-layout p:after {
  content: '';
  width: 10px;
  height: 10px;
  margin-left: -0.2em;
  background: #007fff;
  position: absolute;
  display: inline-block;
  margin-top: 0.7em;
}
</style>
