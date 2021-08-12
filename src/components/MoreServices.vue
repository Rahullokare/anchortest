<template>
  <section class="more">
    <div class="recommend2">
      <h1 class="heading">More Services By Elizabeth Keen</h1>

      <swiper
        :slidesPerView="2"
        :spaceBetween="0"
        :slidesPerGroup="2"
        :loop="true"
        :loopFillGroupWithBlank="true"
        :navigation="true"
        :breakpoints="{
          '240': {
            slidesPerView: 2,
            spaceBetween: 0,
          },
          '640': {
            slidesPerView: 3,
            spaceBetween: 0,
          },
          '768': {
            slidesPerView: 3,
            spaceBetween: 0,
          },
          '1024': {
            slidesPerView: 2,
            spaceBetween: 10,
          },
        }"
        class="mySwiper"
      >
        <swiper-slide> <SellersCard2 /></swiper-slide>
        <swiper-slide> <SellersCard2 /></swiper-slide>
        <swiper-slide> <SellersCard2 /></swiper-slide>
        <swiper-slide> <SellersCard2 /></swiper-slide>
        <swiper-slide> <SellersCard2 /></swiper-slide>
        <swiper-slide> <SellersCard2 /></swiper-slide>
      </swiper>
    </div>
  </section>
</template>

<script>
import SellersCard2 from "./SellerCard2.vue";
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/swiper-bundle.css";
import "swiper/components/pagination/pagination.min.css";
import "swiper/components/navigation/navigation.min.css";

// import Swiper core and required modules
import SwiperCore, { Pagination, Navigation } from "swiper/core";

// install Swiper modules
SwiperCore.use([Pagination, Navigation]);

export default {
  components: { SellersCard2, Swiper, SwiperSlide },
};
</script>

<style >
.more {
  background-color: #fafafa;
}
.recommend2 {
  margin-bottom: 64px;
  background-color: #fafafa;

  padding: 32px 32px 48px;
  /* background-color: red; */
}
.heading {
  padding-bottom: 20px;
  font-size: 20px;
  line-height: 28px;
}

.swiper-button-prev,
.swiper-button-next {
  color: red !important;
  background-color: white;
  color: #4a4a4a !important;
  box-shadow: 0 2px 5px 0 rgb(0 0 0 / 15%);
  border-radius: 10px;
}
.swiper-button-prev:after,
.swiper-container-rtl .swiper-button-next:after {
  content: "prev";
  font-size: 20px;
  padding: 4px;
}
.swiper-button-next:after,
.swiper-container-rtl .swiper-button-next:after {
  content: "next";
  font-size: 20px;
  padding: 4px;
}
</style>