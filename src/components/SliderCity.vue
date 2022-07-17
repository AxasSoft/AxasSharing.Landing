<template>
<div class="city">
    <div class="city__title">
        Поиск вместе с нами
    </div>
    <div class="city__text">
        Это тысячи актуальных квартир от застройщиков, планировки и поэтажные планы, профессионально созданные рендеры, подробные презентации объектов
    </div>
    <swiper
        :navigation="true" 
        
        :modules="modules" 
        class="mySwiper"
        :slides-per-view="2"
        style="margin-bottom: 80px; max-width: 1400px;"
    >
        <swiper-slide> <div class="city__wrapImg"> <div class="city__imgTitle">Краснодар</div><div class="city__imgText">Grand Palace</div> <img src="@/assets/av1.jpg" class="city__img"></div></swiper-slide>
        <swiper-slide> <div class="city__wrapImg"> <div class="city__imgTitle">Краснодар</div><div class="city__imgText">Avrora</div> <img src="@/assets/av2.jpg" class="city__img"></div></swiper-slide>
        <swiper-slide> <div class="city__wrapImg"> <div class="city__imgTitle">Краснодар</div><div class="city__imgText">Ural</div><img src="@/assets/av3.jpg" class="city__img"></div></swiper-slide>
        <swiper-slide> <div class="city__wrapImg"> <div class="city__imgTitle">Краснодар</div><div class="city__imgText">Fresh</div><img src="@/assets/av4.jpg" class="city__img"></div></swiper-slide>
        <swiper-slide> <div class="city__wrapImg"> <div class="city__imgTitle">Краснодар</div><div class="city__imgText">Novella</div><img src="@/assets/av5.jpg" class="city__img"></div></swiper-slide>
        <swiper-slide> <div class="city__wrapImg"> <div class="city__imgTitle">Краснодар</div><div class="city__imgText">Смородина</div><img src="@/assets/av6.jpg" class="city__img"></div></swiper-slide>
        <swiper-slide> <div class="city__wrapImg"> <div class="city__imgTitle">Сочи</div><div class="city__imgText">Кислород</div><img src="@/assets/av7.jpg" class="city__img"></div></swiper-slide>
        <swiper-slide> <div class="city__wrapImg"> <div class="city__imgTitle">Сочи</div><div class="city__imgText">Летний</div><img src="@/assets/av8.jpg" class="city__img"></div></swiper-slide>



    </swiper>
</div>

</template>
<script>
import { Swiper, SwiperSlide } from 'swiper/vue';
import { Navigation } from 'swiper';
import "swiper/css";

import "swiper/css/navigation";


 export default {
    components: {
      Swiper,
      SwiperSlide,
    },
    data(){
        return{
            modules:[
                Navigation,
            ]
        }
    }
 }

</script>