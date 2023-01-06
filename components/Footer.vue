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

            integrations: ["Marketplaces", "Shopping Carts", "Shipping Partners", "Financials"],
            companys: ["Why Inventory Ahead", "Pricing", "YouTube", "Help Center", "Contact Us", "Term and Conditions", "Affiliate Program", "Visit Our App"],
        }
    }
}
</script>

<template>
    <footer class="bg-main_dark">
        <div class="footer-top pt-[100px] pb-[90px]">
            <div class="container mx-auto text-white">
                <div class="grid grid-cols-12">
                    <div class="footer-widget col-span-3">
                        <h5 class="text-lg font-semibold text-dark6 pb-5">Features</h5>
                        <ul class="">
                            <li v-for="featuresMenu in featuresMenus">
                                <NuxtLink to="/" class="text-base font-medium leading-8 text-dark4 hover:text-secondary hover:underline hover:underline-offset-1 transition-all duration-200 ">{{ featuresMenu }}</NuxtLink>
                            </li>
                        </ul>
                    </div>
                    <div class="footer-widget col-span-2 -ml-2">
                        <h5 class="text-lg font-semibold text-dark6 pb-5">Integrations</h5>
                        <ul class="">
                            <li v-for="integration in integrations">
                                <NuxtLink to="/" class=" text-base font-medium leading-8 text-dark4 hover:text-secondary hover:underline hover:underline-offset-1 transition-all duration-200">{{ integration }}</NuxtLink>
                            </li>
                        </ul>
                    </div>
                    <div class="footer-widget col-span-3">
                        <h5 class="text-lg font-semibold text-dark6 pb-5">Company</h5>
                        <ul class="">
                            <li v-for="company in companys">
                                <NuxtLink to="/" class=" text-base font-medium leading-8 text-dark4 hover:text-secondary hover:underline hover:underline-offset-1 transition-all duration-200">{{ company }}</NuxtLink>
                            </li>
                        </ul>
                    </div>
                    <div class="footer-widget col-span-4">
                        <h5 class="text-lg font-semibold text-dark6 pb-5">Contact us</h5>
                        <ul class=" flex flex-col gap-1 pb-8">
                            <li class="flex gap-3 items-center">
                                <span>
                                    <svg width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                                        <path d="M16.4775 13.7475C16.4775 14.0175 16.4175 14.295 16.29 14.565C16.1625 14.835 15.9975 15.09 15.78 15.33C15.4125 15.735 15.0075 16.0275 14.55 16.215C14.1 16.4025 13.6125 16.5 13.0875 16.5C12.3225 16.5 11.505 16.32 10.6425 15.9525C9.78 15.585 8.9175 15.09 8.0625 14.4675C7.2 13.8375 6.3825 13.14 5.6025 12.3675C4.83 11.5875 4.1325 10.77 3.51 9.915C2.895 9.06 2.4 8.205 2.04 7.3575C1.68 6.5025 1.5 5.685 1.5 4.905C1.5 4.395 1.59 3.9075 1.77 3.4575C1.95 3 2.235 2.58 2.6325 2.205C3.1125 1.7325 3.6375 1.5 4.1925 1.5C4.4025 1.5 4.6125 1.545 4.8 1.635C4.995 1.725 5.1675 1.86 5.3025 2.055L7.0425 4.5075C7.1775 4.695 7.275 4.8675 7.3425 5.0325C7.41 5.19 7.4475 5.3475 7.4475 5.49C7.4475 5.67 7.395 5.85 7.29 6.0225C7.1925 6.195 7.05 6.375 6.87 6.555L6.3 7.1475C6.2175 7.23 6.18 7.3275 6.18 7.4475C6.18 7.5075 6.1875 7.56 6.2025 7.62C6.225 7.68 6.2475 7.725 6.2625 7.77C6.3975 8.0175 6.63 8.34 6.96 8.73C7.2975 9.12 7.6575 9.5175 8.0475 9.915C8.4525 10.3125 8.8425 10.68 9.24 11.0175C9.63 11.3475 9.9525 11.5725 10.2075 11.7075C10.245 11.7225 10.29 11.745 10.3425 11.7675C10.4025 11.79 10.4625 11.7975 10.53 11.7975C10.6575 11.7975 10.755 11.7525 10.8375 11.67L11.4075 11.1075C11.595 10.92 11.775 10.7775 11.9475 10.6875C12.12 10.5825 12.2925 10.53 12.48 10.53C12.6225 10.53 12.7725 10.56 12.9375 10.6275C13.1025 10.695 13.275 10.7925 13.4625 10.92L15.945 12.6825C16.14 12.8175 16.275 12.975 16.3575 13.1625C16.4325 13.35 16.4775 13.5375 16.4775 13.7475Z" stroke="#4AF8E3" stroke-width="1.5" stroke-miterlimit="10"/>
                                        <path d="M13.875 6.75C13.875 6.3 13.5225 5.61 12.9975 5.0475C12.5175 4.53 11.88 4.125 11.25 4.125" stroke="#4AF8E3" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                                        <path d="M16.5 6.75C16.5 3.8475 14.1525 1.5 11.25 1.5" stroke="#4AF8E3" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                                    </svg>
                                </span>
                                <NuxtLink to="tel:+18772240561" class=" text-base font-medium leading-8 text-dark4 hover:text-secondary hover:underline hover:underline-offset-1 transition-all duration-200">
                                    1.877.224.0561
                                </NuxtLink>
                            </li>
                            <li class="flex gap-3 items-center">
                                <span>
                                    <svg width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                                        <path d="M12.75 15.375H5.25C3 15.375 1.5 14.25 1.5 11.625V6.375C1.5 3.75 3 2.625 5.25 2.625H12.75C15 2.625 16.5 3.75 16.5 6.375V11.625C16.5 14.25 15 15.375 12.75 15.375Z" stroke="#4AF8E3" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
                                        <path d="M12.75 6.75L10.4025 8.625C9.63 9.24 8.3625 9.24 7.59 8.625L5.25 6.75" stroke="#4AF8E3" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
                                    </svg>
                                </span>
                                <NuxtLink to="mailto:support@inventoryahead.com" class="text-base font-medium leading-8 text-dark4 hover:text-secondary hover:underline hover:underline-offset-1 transition-all duration-200">
                                    support@inventoryahead.com
                                </NuxtLink>
                            </li>
                        </ul>
                        <div class="subscribe-newsletter">
                            <h6 class=" text-lg font-semibold leading-6 text-dark5 mb-5">
                                Subscribe to our Newsletter
                            </h6>
                            <div class="pb-10">
                                <div class="relative mt-1 rounded-md shadow-sm">
                                    <div class="pointer-events-none absolute inset-y-0 left-0 flex items-center pl-[25px]">
                                        <span class="">
                                            <svg width="17" height="17" viewBox="0 0 17 17" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <path d="M12.0417 14.5208H4.95835C2.83335 14.5208 1.41669 13.4583 1.41669 10.9791V6.02079C1.41669 3.54163 2.83335 2.47913 4.95835 2.47913H12.0417C14.1667 2.47913 15.5834 3.54163 15.5834 6.02079V10.9791C15.5834 13.4583 14.1667 14.5208 12.0417 14.5208Z" stroke="#BAB8CF" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path d="M12.0416 6.375L9.82456 8.14583C9.09498 8.72667 7.89789 8.72667 7.16831 8.14583L4.95831 6.375" stroke="#BAB8CF" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
                                            </svg>
                                        </span>
                                    </div>

                                    <input type="text" name="price" id="price" class="block w-full bg-transparent border-2 rounded-lg h-[58px] border-dark_shade pl-[50px] pr-12 text-base font-medium leading-[18px] transition-colors duration-200 focus:border-secondary focus:outline-none text-dark4" placeholder="Enter email">

                                    <div class="absolute inset-y-0 right-0 flex items-center">
                                        <NuxtLink to="/" class="bg-secondary h-full w-20 rounded-lg grid items-center justify-center hover:bg-secondary/90 transition-colors duration-200">
                                            <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                <path d="M6.16665 5.26667L13.2417 2.90834C16.4167 1.85001 18.1417 3.58334 17.0917 6.75834L14.7333 13.8333C13.15 18.5917 10.55 18.5917 8.96665 13.8333L8.26665 11.7333L6.16665 11.0333C1.40832 9.45001 1.40832 6.85834 6.16665 5.26667Z" stroke="#06021C" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                                <path d="M8.42499 11.375L11.4083 8.3833" stroke="#06021C" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                            </svg>
                                        </NuxtLink>
                                    </div>
                                </div>
                            </div>
                            <div class="signUp-demo-btn flex gap-5 max-w-xs">
                                <NuxtLink to="/registrationv2" class=" w-full">
                                    <button type="submit" class=" group relative flex items-center w-full justify-center rounded-md bg-main_purple text-lg py-2 px-4 h-[58px] font-semibold text-white hover:bg-main_purple/70 transition-all duration-200 focus:outline-none">
                                        
                                        Sign up
                                    </button>
                                </NuxtLink>
                                <NuxtLink to="/"  class=" w-full">
                                    <button type="submit" class="group relative flex items-center w-full justify-center rounded-md bg-white hover:bg-white/80 transition-all duration-200 text-lg py-2 px-4 font-semibold text-main_purple focus:outline-none h-[58px]">
                                        
                                        Free Demo
                                    </button>
                                </NuxtLink>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="footer-bottom py-[18px] border-t border-white/20">
            <div class="container mx-auto text-white">
                <div class="grid grid-cols-2 text-base font-medium text-dark4">
                    <div class="copy-write">
                        Copyright © 2022 <NuxtLink to="/" class=" text-secondary uppercase hover:underline hover:underline-offset-1">INVENTORY AHEAD LLC</NuxtLink>. All rights reserved.
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