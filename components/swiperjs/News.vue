<template>
  <div>
    <swiper class="swiper" :options="swiperOption">
      <swiper-slide>
        <img src="/img/news/1.png" style="width: 100%">
        <span>2022/01/05</span>
        <a>全球青年的倡导与计划大会</a>
        <p>为年轻人被赋予支持并鼓励他们充分发挥其作为全球公民的潜力的社会而奋斗，增加创造力的产生。</p>
      </swiper-slide>
      <swiper-slide>
        <img src="/img/news/2.png" style="width: 100%">
        <span>2022/03/01</span>
        <a>Gendered attitude towards human trafficking survivors
        </a>
        <p>A leading national daily of Bangladesh reports that around 1,000 women have returned from only Saudi Arabia to Bangladesh since January 2018.</p>
      </swiper-slide>
      <swiper-slide>
        <img src="/img/news/3.png" style="width: 100%">
        <span>2022/04/21</span>
        <a>开放性教育在互联网中的实践</a>
        <p>建立在开放基础上的教育运动，它与其他教育运动区别在于，扩大社会的参与度和包容性。</p>
      </swiper-slide>
      <swiper-slide>
        <img src="/img/news/4.png" style="width: 100%">
        <span>2022/04/25</span>
        <a>RFC 6335 面向网络安全的扩展</a>
        <p>从端口的使用场景和范围以及利用途径、攻击方法和可用性、完整性、保密性来对端口漏洞进行建立模型。</p>
      </swiper-slide>
      <swiper-slide>
        <img src="/img/news/5.png" style="width: 100%">
        <span>2022/05/03</span>
        <a>Log4j 系列漏洞对于传统传输协议的启示</a>
        <p>Log4j 系列漏洞理论上主要通过依赖于传输协议来通过日志的方式来出发恶意命令执行等相关问题。</p>
      </swiper-slide>
      <swiper-slide>
        <img src="/img/news/6.png" style="width: 100%">
        <span>2022/05/29</span>
        <a>Recent Transport Protocols in Wired Networks and Internet</a>
        <p>Goal: Study and analysis the performance of standard transport protocols (TCP, UDP) as well as recent protocol (SCTP, DCCP, MTCP) with varying different parameters </p>
      </swiper-slide>
      <div class="swiper-pagination" slot="pagination"></div>
    </swiper>
  </div>
</template>

<script>
import { Swiper, SwiperSlide } from 'vue-awesome-swiper'

export default {
  name: "News",
  components: {
    Swiper,
    SwiperSlide
  },
  data() {
    return {
      swiperOption: {
        slidesPerView: 6,
        spaceBetween: 20,
        pagination: {
          el: '.swiper-pagination',
          clickable: true
        },
      }
    }
  }
}
</script>

<style scoped>
  div {
    display: block;
    height: 490px;
  }
  >>> .swiper-slide {
    display: inline-table;
    width: 328px !important;;
    height: 392px;
    background: #FFFFFF;
    box-shadow: 0px 4px 16px rgba(0, 0, 0, 0.09);    margin-left: 30px;
    margin-bottom: 30px;
    margin-top: 20px;
    padding: 18px;
  }
  >>> .swiper {
    display: table-header-group;
    position: absolute;
    left: 0;
  }
  >>> .swiper-pagination-bullet-active{
    display: inline-block;
    /* border-radius: 100%; */
    background: #007FFF;
    opacity: 1;
  }
  >>> .swiper-pagination-bullet {
    display: inline-block;
    /* border-radius: 100%; */
    background: #007FFF;
    opacity: 0.1;
    left: 0;
    width: 9%;
    margin-top: 33px;
  }
  >>> .swiper-pagination-fraction, .swiper-pagination-custom, .swiper-container-horizontal > .swiper-pagination-bullets {
    text-align: left;
    position: sticky;
    width: 100%;
    height: 0px;
    background: #007FFF;
  }
  span {
    color: #007FFF;
    margin-top: 10px;
    margin-bottom: 10px;
    display: block;
  }
  a {
    color: #3E5E7E;
    font-family: SourceHanSerifCN-Bold;
    cursor: pointer;
  }
  p {
    color: #8A8A8A;
    margin-top: 5px;
    font-family: SourceHanSerifCN-Regular;
    font-weight: 100;
  }
  @media screen and (max-width: 1534px) {
    .swiper-slide {
      display: inline-table;
      width: 76% !important;
      height: auto !important;
      background: #FFFFFF;
      box-shadow: 0px 4px 16px rgb(0 0 0 / 9%);
       margin-left: 0 !important;
       margin-bottom: 0 !important;
      margin-top: 20px;
      padding: 1em !important;
    }
    .swiper-pagination-fraction, .swiper-pagination-custom, .swiper-container-horizontal > .swiper-pagination-bullets {
      display: none !important;
    }
    .swiper-slide p {
      padding-left: 1em !important;
      padding-right: 1em !important;
      display: block;
      padding-bottom: 3em !important;
    }
    .swiper-slide a {
      padding-left: 1em !important;
      padding-right: 1em !important;
      display: block;
    }
    .swiper-slide span {
      padding-left: 1em !important;
      padding-right: 1em !important;
      padding-top: 1em !important;
    }
  }
</style>
