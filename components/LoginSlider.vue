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
            class="mySwiper"
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

<script>
    import './loginslider.css';
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

