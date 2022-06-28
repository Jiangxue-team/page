<template>
  <div class="ov-layout">
    <p class="ov-font-layout">位于繁华都市之中，成员遍布全球，退居山水之间，传千年之经义，燃万古之明灯<br>
      知一传百，思而故行，学以致用，护之国网<br>
      “因为热爱，方可无惧”
    </p>
    <swiper class="swiper" :options="swiperOption">
      <swiper-slide>
        <img src="/img/overview/natural-Funding-projects.png" />
        <p><span>13</span>项</p>
        <span>
          2022首批开放参与自然资金项目
        </span>
      </swiper-slide>
      <swiper-slide>
        <img src="/img/overview/knowledge-storage.png" />
        <p><span>12.3</span>千册/件</p>
        <span>
          知识库存储领域及学科书籍
        </span>
      </swiper-slide>
      <swiper-slide>
        <img src="/img/overview/office-node.png" />
        <p><span>15</span>个</p>
        <span>
          全球分组办公节点网络
        </span>
      </swiper-slide>
      <swiper-slide>
        <img src="/img/overview/to-leave.png" />
        <p><span>235</span>人</p>
        <span>
          江雪走出，为领域发光发热
        </span>
      </swiper-slide>
      <swiper-slide>
        <img src="/img/overview/knowledge-base-learner.png" />
        <p><span>10196</span>人</p>
        <span>
          知识库在学人数（本团队132人，社区9532人，其他532人）
        </span>
      </swiper-slide>
      <div class="swiper-pagination" slot="pagination"></div>
    </swiper>
  </div>
</template>

<script>
import { Swiper, SwiperSlide } from 'vue-awesome-swiper'

export default {
  name: "Overview",
  components: {
    Swiper,
    SwiperSlide
  },
  data() {
    return {
      swiperOption: {
        slidesPerView: 5,
        spaceBetween: 38,
        pagination: {
          el: '.swiper-pagination',
          clickable: true
        }
      }
    }
  }
}
</script>

<style scoped>
swiper-slide {
}
  .ov-layout {
    background: url(/img/banner-towers.png) 0% 0% / 100%;
    height: 717px;
    margin-top: 60px;
  }
  .ov-font-layout {
    text-align: center;
    font-family: SourceHanSerifCN-Regular;
    color: #3E5E7E;
    font-size: 16px;
    padding-top: 153px;
  }
  >>> .swiper-slide {
    margin-top: 88px;
    height: 326.09px;
    text-align: center;
  }
  >>> .swiper-pagination {
    position: inherit;
  }
  >>> .swiper-pagination-bullet-active {
    background: url("/img/streamer/ui/selected.png") 0% 0% / 20px 20px !important;
    width: 20px !important;
    height: 20px !important;
  }
  >>> .swiper-pagination-bullet {
    background: url("/img/streamer/ui/unchecked.png") 0% 0% / 20px 20px !important;
    width: 20px !important;
    height: 20px !important;
    margin-left: 10px;
    margin-top: 30px;
  }
  img {
    width: 211.77px;
    height: 206.57px;
    text-align: center !important;
  }
  .swiper p {
    margin-top: 25px;
    font-size: 15px;
    font-family: SourceHanSerifCN-Bold;
    color: #3E5E7E;
  }
  .swiper p span {
    font-size: 25px;
    color: #007FFF;
    font-family: SourceHanSerifCN-Bold;
  }
  .swiper span {
    color: #3E5E7E;
    font-size: 15px;
  }
</style>
