<script>
    export default {
        
    }
</script>

<template>
    <div class="hero-area-wrap z-10 grid min-h-dvh">
        <div class="container px-4">
            <div class="max-w-[705px] pt-[110px] md:pt-[170px] pb-[250px] md:pb-[270px]">
                <div class="col-span-6 text-white text-center md:text-start">
                    <h1 class="text-[42px] lg:text-[84px] leading-[1.09em] font-normal">
                        <span class="font-black">Systemize</span> your <span class="font-black text-nowrap">e-commerce</span> company
                    </h1>
                    <p class="mt-8 mb-12 text-base font-medium leading-[1.55em]">
                        End-to-end e-commerce management
                    </p>

                    <div class="flex gap-5 flex-col">
                        <div class="flex gap-5 flex-col md:flex-row">
                            <PrimaryBtn>Book a Demo</PrimaryBtn>
                            <SecondaryBtn>Sign up today</SecondaryBtn>
                        </div>
                        <div class="">
                            <NuxtLink to="/" class="inline-flex gap-2 py-3 md:py-[18px] px-7 text-white text-base md:text-lg font-semibold font-roobert items-center justify-center bg-[#f5f3fd]/20 hover:bg-secondary/20 backdrop-blur-[20px] transition-all duration-200 w-full max-w-[430px] rounded-lg h-[50px] md:h-[58px]">
                                <span>
                                    <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                        <path d="M3.3335 10.0001V7.03341C3.3335 3.35007 5.94183 1.84174 9.1335 3.68341L11.7085 5.16674L14.2835 6.65007C17.4752 8.49174 17.4752 11.5084 14.2835 13.3501L11.7085 14.8334L9.1335 16.3167C5.94183 18.1584 3.3335 16.6501 3.3335 12.9667V10.0001Z" stroke="white" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
                                    </svg>
                                </span>
                                <span>Watch the video</span>
                            </NuxtLink>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.hero-area-wrap {
    background: url('../assets/img/hero-bg.jpg');
    background-size: cover, cover;
    background-repeat: no-repeat, no-repeat;
}


</style>