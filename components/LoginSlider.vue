<script>
import { Swiper, SwiperSlide } from 'swiper/vue';
import { Pagination, Autoplay, Mousewheel } from "swiper";
import "swiper/css/pagination";
import 'swiper/css';


export default {
    name: "LoginSlider",

    components: {
        Swiper,
        SwiperSlide,
    },
    setup() {
        const onSwiper = (swiper) => {
            console.log(swiper);
        };
        const onSlideChange = () => {
            console.log('slide change');
        };
        return {
            onSwiper,
            onSlideChange,
            modules: [Pagination, Autoplay, Mousewheel],
        };
    },
};
</script>

<template>
    <div>
        <div class="justify-start">
    
            <swiper 
            :slides-per-view="1"
            :space-between="0"
            :speed="1200"
            :loop="true"
            :loopFillGroupWithBlank="true"
            :mousewheel="true"
            :direction="'vertical'" 
            :modules="modules"
            @swiper="onSwiper"
            @slideChange="onSlideChange"
            class="loginSlider"
            :autoplay="{
                delay: 5000,
                disableOnInteraction: false,
            }"
            :pagination="{
                clickable: true,
            }"
            >
                <swiper-slide class="">
                    <div class="slide-content relative z-10 mx-auto">
                        <div class="quote-icon">
                            <img src="../assets/img/login-quote-icon.png" class=" w-[118px]">
                        </div>
                        <h2 class="text-[2.5rem] leading-[3.25rem] text-white font-normal">
                            Inventory Management is not the <span class=" font-bold">main thing</span> to success, its
                            the <span class="font-bold">ONLY</span> thing to success.
                        </h2>
                    </div>
                </swiper-slide>
                <swiper-slide class="">
                    <div class="slide-content relative z-10 mx-auto">
                        <div class="quote-icon">
                            <img src="../assets/img/login-quote-icon.png" class=" w-[118px]">
                        </div>
                        <h2 class="text-[2.5rem] leading-[3.25rem] text-white font-normal">
                            A good system <span class=" font-bold">shortens</span> the road to the goal
                        </h2>
                    </div>
                </swiper-slide>
                <swiper-slide class="">
                    <div class="slide-content relative z-10 mx-auto">
                        <div class="quote-icon">
                            <img src="../assets/img/login-quote-icon.png" class=" w-[118px]">
                        </div>
                        <h2 class="text-[2.5rem] leading-[3.25rem] text-white font-normal">
                            <span class=" font-bold">Systemize</span> your <span class="font-bold">e-commerce</span>
                            company.
                        </h2>
                    </div>
                </swiper-slide>
            </swiper>
        </div>
    </div>
</template>

<style>
.loginSlider {
    height: 100vh;
    /* background: url('../assets/img/login-2-bg.jpg') no-repeat !important;
    background-size: cover; */
}

.slider-bg {
    background: url('../assets/img/login-2-bg.jpg') no-repeat;
    background-size: cover;
    min-height: 100svb;
    height: 100%;
}
.loginSlider .swiper-slide {
    text-align: start;    
    display: flex;
    justify-content: start;
    align-items: center;
}

.loginSlider .slide-content {
    max-width: 540px;
    text-align: start;
    padding-right: 50px;
}
.loginSlider .swiper-pagination-bullet {
    background: rgba(255, 255, 255, 1);
    height: 8px;
    width: 8px;
    margin: 10px 0 !important;
    opacity: 0.2;
}
.loginSlider .swiper-pagination-bullet-active {
    background: #4AF8E3;
    height: 8px;
    width: 8px;
    opacity: 1;
}
.loginSlider .swiper-pagination {
    left: 40px;
}

.quote-icon {
    position: absolute;
    left:-44px;
    top: -85px;
    z-index: -10;
}
</style>


