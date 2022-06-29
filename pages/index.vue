<template>
  <div>
    <div class="page-index">
      <streamer />
      <Abstract />
      <news />
      <engineering-plan />
      <img src="/img/engineering-plan.png" />
      <important-proposal />
      <join-us />
      <overview />
    </div>
    <index />
  </div>
</template>

<script>
import Streamer from "~/components/swiperjs/Streamer";
import Abstract from "~/components/Abstract";
import News from "~/components/swiperjs/News";
import Overview from "~/components/swiperjs/Overview";
import Index from "~/components/mobile/page/Index";
export default {
  name: 'IndexPage',
  components: {
    Overview,
    News,
    Streamer,
    Abstract,
    Index
  },
}
</script>
