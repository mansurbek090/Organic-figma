<template>
  <swiper
    ref="{swiperRef}"
    :slidesPerView="3"
    :centeredSlides="true"
    :spaceBetween="10"
    :pagination="{
      type: 'fraction',
    }"
    :navigation="true"
    :loop="true"
    :modules="modules"
    class="mySwiper"
  >
  
     <swiper-slide>
      <img src="../../assets/aboutImages/p-17.svg" alt="p-17" loading="lazy" width="330">
      <b>Spicy</b>
    </swiper-slide>
    <swiper-slide>
      <img src="../../assets/aboutImages/p-18.svg" alt="p-18" loading="lazy" width="330">
      <b>Nuts & Feesd</b>
    </swiper-slide>
    <swiper-slide>
      <img src="../../assets/aboutImages/p-19.png" alt="p-19" loading="lazy" width="330">
      <b>Fruits</b>
    </swiper-slide>
    <swiper-slide>
      <img src="../../assets/aboutImages/p-20.png" alt="p-20" loading="lazy" width="330">
      <b>Vegetable</b>
    </swiper-slide>
   
  </swiper>

  <p class="append-buttons"></p>
</template>
<script>
  // Import Swiper Vue.js components
  import { Swiper, SwiperSlide } from 'swiper/vue';

  // Import Swiper styles
  import 'swiper/css';

  import 'swiper/css/pagination';
  import 'swiper/css/navigation';

  import './ibrohimsSwiper.css';

  // import required modules
  import { Pagination, Navigation } from 'swiper/modules';

  export default {
    components: {
      Swiper,
      SwiperSlide,
    },
    setup() {
      return {
        modules: [Pagination, Navigation],
      };
    },
  };
</script>
