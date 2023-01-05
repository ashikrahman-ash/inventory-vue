<script>

import facebookIcon from '../assets/img/facebook.svg'
import twitterIcon from '../assets/img/twitter.svg'
import instagramIcon from '../assets/img/instagram.svg'
import youtubeIcon from '../assets/img/youtube.svg'

export default {

    data() {
        return {
            facebookIcon,
            twitterIcon,
            instagramIcon,
            youtubeIcon,

            featuresMenus: ["Purchasing & Receiving", "Inventory" , "Products", "Listings", "Reorder", "Replenish", "Order Fulfillment", "FBA Shipments", "Profit and Reports", "User Permission"],
        }
    }
}
</script>

<template>
    <footer class="bg-main_dark">
        <div class="footer-top pt-[100px] pb-[90px]">
            <div class="container mx-auto text-white">
                <div class="footer-widget">
                    <h5 class="text-lg font-semibold text-dark6 pb-5">Features</h5>
                    <ul class="">
                        <li v-for="featuresMenu in featuresMenus">
                            <NuxtLink to="/" class=" text-base font-medium leading-8 text-dark4">{{ featuresMenu }}</NuxtLink>
                        </li>
                    </ul>
                </div>
            </div>
        </div>

        <div class="footer-bottom py-[18px] border-t border-white/20">
            <div class="container mx-auto text-white">
                <div class="grid grid-cols-2 text-base font-medium text-dark4">
                    <div class="copy-write">
                        Copyright © 2022 <NuxtLink to="/" class=" text-secondary uppercase">INVENTORY AHEAD LLC</NuxtLink>. All rights reserved.
                    </div>
                    <div class="social-media flex gap-5 justify-end">
                        <div class="">
                            Stay Connected:
                        </div>
                        <NuxtLink to="/">
                            <img :src="facebookIcon" alt="fb icon" class="max-w-full w-auto">
                        </NuxtLink>
                        <NuxtLink to="/">
                            <img :src="twitterIcon" alt="fb icon" class="max-w-full w-auto">
                        </NuxtLink>
                        <NuxtLink to="/">
                            <img :src="instagramIcon" alt="fb icon" class="max-w-full w-auto">
                        </NuxtLink>
                        <NuxtLink to="/">
                            <img :src="youtubeIcon" alt="fb icon" class="max-w-full w-auto">
                        </NuxtLink>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>


<style scoped>

</style>