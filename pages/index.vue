
<script>
import serviceIcon1 from '../assets/img/services-icon-1.png'
import serviceIcon2 from '../assets/img/services-icon-2.png'
import serviceIcon3 from '../assets/img/services-icon-3.png'
import serviceIcon4 from '../assets/img/services-icon-4.png'
import serviceIcon5 from '../assets/img/services-icon-5.png'
import serviceIcon6 from '../assets/img/services-icon-6.png'

import expandProfit from '../assets/img/inventory-char.png'
import flexibleFacility from '../assets/img/flexible-facility.png'

import flexibleIcon1 from '../assets/img/flexible-list-icon-1.svg'
import flexibleIcon2 from '../assets/img/flexible-list-icon-2.svg'
import flexibleIcon3 from '../assets/img/flexible-list-icon-3.svg'

// Brand Logos
import fedex from '../assets/img/fedex-logo.png'
import shopify from '../assets/img/shopify-logo.png'
import quickbooks from '../assets/img/quickbooks-logo.png'
import woocommerce from '../assets/img/woocommerce-logo.png'
import shipping from '../assets/img/shipping-logo.png'
import ups from '../assets/img/ups-logo.png'
import walmart from '../assets/img/walmart-logo.png'
import ebay from '../assets/img/ebay-logo.png'
import amazon from '../assets/img/amazon-logo.png'


//Inventory profit cart
import manegeControl from '../assets/img/manege-control.svg'
import accurateData from '../assets/img/accurate-data.svg'
import workflowIllustration from '../assets/img/work-flow-illustration.svg'
import workFlowStepIcon from '../assets/img/work-flow-step-icon.svg'


export default {
    data() {
        return {
            expandProfit,
            flexibleFacility,
            manegeControl,
            accurateData,
            workflowIllustration,
            workFlowStepIcon,

            services: [
                {
                    id: 1,
                    icon: serviceIcon1,
                    title: "Inventory made Easy",
                    content: "Track products from inventory till fulfillment so that nothing falls thru the cracks"
                },
                {
                    id: 2,
                    icon: serviceIcon2,
                    title: "Single Platform",
                    content: "Manage your inventory from purchasing to accounting"
                },
                {
                    id: 3,
                    icon: serviceIcon3,
                    title: "Think Ahead",
                    content: "Predict reordering based on demand, season and most profitable items."
                },
                {
                    id: 4,
                    icon: serviceIcon4,
                    title: "Be in Control",
                    content: "Track products from inventory till fulfillment so that nothing falls thru the cracks"
                },
                {
                    id: 5,
                    icon: serviceIcon5,
                    title: "User Friendly",
                    content: "Track products from inventory till fulfillment so that nothing falls thru the cracks"
                },
                {
                    id: 6,
                    icon: serviceIcon6,
                    title: "Mobile Friendly",
                    content: "Track products from inventory till fulfillment so that nothing falls thru the cracks"
                }
            ],
            flexibleListItems: [
                {
                    icon: flexibleIcon1,
                    title: "Custom dashboards",
                },
                {
                    icon: flexibleIcon2,
                    title: "Grant permission to multiple users and manage their permission levels",
                },
                {
                    icon: flexibleIcon3,
                    title: "Customize the filters according to your needs and liking. ",
                },
            ],

            brandLogos: [
                {
                    logo: fedex,
                    altText: "FedEx logo",
                },
                {
                    logo: shopify,
                    altText: "Shopify logo",
                },
                {
                    logo: quickbooks,
                    altText: "Quickbooks logo",
                },
                {
                    logo: woocommerce,
                    altText: "Woocommerce logo",
                },
                {
                    logo: shipping,
                    altText: "Shipping logo",
                },
                {
                    logo: ups,
                    altText: "Ups logo",
                },
                {
                    logo: walmart,
                    altText: "Walmart logo",
                },
                {
                    logo: ebay,
                    altText: "Ebay logo",
                },
                {
                    logo: amazon,
                    altText: "Amazon logo",
                },
                
                {
                    logo: fedex,
                    altText: "FedEx logo",
                },
                {
                    logo: shopify,
                    altText: "Shopify logo",
                },
                {
                    logo: quickbooks,
                    altText: "Quickbooks logo",
                },
                {
                    logo: woocommerce,
                    altText: "Woocommerce logo",
                },
                {
                    logo: shipping,
                    altText: "Shipping logo",
                },
                {
                    logo: ups,
                    altText: "Ups logo",
                },
                {
                    logo: walmart,
                    altText: "Walmart logo",
                },
                {
                    logo: ebay,
                    altText: "Ebay logo",
                },
                {
                    logo: amazon,
                    altText: "Amazon logo",
                },
            ],
            brandLogos2: [
                {
                    logo: fedex,
                    altText: "FedEx logo",
                },
                {
                    logo: shopify,
                    altText: "Shopify logo",
                },
                {
                    logo: quickbooks,
                    altText: "Quickbooks logo",
                },
                {
                    logo: woocommerce,
                    altText: "Woocommerce logo",
                },
                {
                    logo: shipping,
                    altText: "Shipping logo",
                },
                {
                    logo: ups,
                    altText: "Ups logo",
                },
                {
                    logo: walmart,
                    altText: "Walmart logo",
                },
                {
                    logo: ebay,
                    altText: "Ebay logo",
                },
                {
                    logo: amazon,
                    altText: "Amazon logo",
                },
                
                {
                    logo: fedex,
                    altText: "FedEx logo",
                },
                {
                    logo: shopify,
                    altText: "Shopify logo",
                },
                {
                    logo: quickbooks,
                    altText: "Quickbooks logo",
                },
                {
                    logo: woocommerce,
                    altText: "Woocommerce logo",
                },
                {
                    logo: shipping,
                    altText: "Shipping logo",
                },
                {
                    logo: ups,
                    altText: "Ups logo",
                },
                {
                    logo: walmart,
                    altText: "Walmart logo",
                },
                {
                    logo: ebay,
                    altText: "Ebay logo",
                },
                {
                    logo: amazon,
                    altText: "Amazon logo",
                },
            ],
        }
    }
}
</script>

<template>
    <div>
        <NuxtLayout>
            <Head>
                <Title>Home | Inventory Ahead Dashboard</Title>
                <Meta name="description" content="Inventory Ahead Dashboard" />
                <Link></Link>
            </Head>

            <HomeHero />

            <!-- /Services area - Start  -->
            <section class="services-wrapper">
                <div class="wide-container mx-auto pt-[100px] pb-[135px] px-40 mt-[-200px] bg-white rounded-[20px]">
                    <div class="services-box grid grid-cols-3 gap-[30px] mb-14">

                        <div v-for="service in services" class="service-item pt-10 px-8 pb-8 bg-dark7 rounded-xl border-2 border-dark7 hover:border-dark5 hover:bg-white transition-colors duration-200">
                            <div class="service-icon mb-8">
                                <img :src="service.icon" alt="" class=" max-w-full">
                            </div>
                            <h3 class="service-heading font-semibold text-dark1 text-4xl mb-5">
                                {{ service.name }}
                            </h3>
                            <p class=" text-dark2 text-lg">
                                {{ service.content }}
                            </p>
                        </div>

                    </div>
                    <div class="text-right">
                        <PrimaryBtn>Free Trial</PrimaryBtn>
                    </div>
                </div>
            </section>
            <!-- /Services area - End  -->

            <!-- /Expand profit - Start  -->
            <section class="expand-profit-wrapper bg-dark1 py-[100px]">
                <div class="container mx-auto">
                    <div class="expand-profit-inner grid grid-cols-2 items-center gap-20">
                        <div class="expand-profit-content grid-cols-1">
                            <h2 class=" text-5xl font-bold leading-[52px] text-white mb-10">
                                Purchase with budget, expand with profit
                            </h2>
                            <p class=" text-base text-dark7 font-normal leading-[26px] mb-5">
                                Easily identify your highest-performing products across channels to improve your sales strategy.
                            </p>
                            <p class=" text-base text-dark7 font-normal leading-[26px]">
                                Avoid overbuying, overstocking on non-essentials, get notifications when your most in demand, profitable items are running low and need immediate restocking
                            </p>
                            <div class="mt-10">
                                <PrimaryBtn>Free demo</PrimaryBtn>
                            </div>
                        </div>
                        <div class="expand-profit-img grid-cols-1 mr-[-74px]">
                            <img :src="expandProfit" alt="" class=" max-w-full w-full">
                        </div>
                    </div>
                </div>
            </section>
            <!-- /Expand profit - End  -->

            <!-- /Flexible facility - Start  -->
            <section class="flexible-facility-wrapper py-[100px]">
                <div class="container mx-auto">
                    <div class="expand-profit-inner grid grid-cols-2 items-center gap-[60px]">
                        <div class="expand-profit-img grid-cols-1 ml-[-160px] -mr-20">
                            <img :src="flexibleFacility" alt="" class="max-w-full w-full">
                        </div>
                        <div class="expand-profit-content grid-cols-1">
                            <h2 class=" text-5xl font-bold leading-[52px] text-dark1 mb-10">
                                Purchase with budget, expand with profit
                            </h2>
                            <div class="border-y border-dark5 max-w-[435px]">
                                <div v-for="flexibleListItem in flexibleListItems" class="list-item-wrap">
                                    <div class="listItem flex gap-4 items-center p-5 rounded-xl bg-white hover:bg-dark7 transition-colors duration-200 hover:cursor-pointer">
                                        <div class="icon w-[42px] shrink-0">
                                            <img :src="flexibleListItem.icon" alt="" class="max-w-full w-full">
                                        </div>
                                        <div class="list-heading">
                                            <p class="text-lg font-medium text-dark2">
                                                {{ flexibleListItem.title }}
                                            </p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="mt-10">
                                <PrimaryBtn>See all features</PrimaryBtn>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <!-- /Flexible facility - End  -->

            <!-- Inventory profit cart / Start  -->
            <section class="inventory-profit-chart bg-dark7 py-[100px]">
                <div class="container mx-auto">
                    <div class="inventoryProfit-inner">
                        <div class="inventory-icon-boxs flex items-center gap-4 mb-[30px]">
                            <div class="single-box bg-white rounded-xl flex gap-5 items-center p-6 flex-auto">
                                <div class="">
                                    <img :src="manegeControl" alt="">
                                </div>
                                <div class="">
                                    <h5 class=" text-dark1 font-bold text-[22px] leading-8 pb-1">
                                        Inventory
                                    </h5>
                                    <p class=" text-main_purple font-medium">
                                        Manage Control
                                    </p>
                                </div>
                            </div>
                            <div class="single-box flex items-center justify-center flex-auto">
                                <span class=" text-dark1 font-bold text-[28px] leading-9">
                                    +
                                </span>
                            </div>
                            <div class="single-box bg-white rounded-xl flex gap-5 items-center p-6 flex-auto">
                                <div class="">
                                    <img :src="accurateData" alt="">
                                </div>
                                <div class="">
                                    <h5 class=" text-dark1 font-bold text-[22px] leading-8 pb-1">
                                        Profit
                                    </h5>
                                    <p class=" text-main_purple font-medium">
                                        Accurate Data Analytics
                                    </p>
                                </div>
                            </div>
                            <div class="single-box flex items-center justify-center flex-auto">
                                <span class=" text-dark1 font-bold text-[28px] leading-9">
                                    =
                                </span>
                            </div>
                            <div class="single-box profit-bg-shape bg-white rounded-xl p-6 max-w-[350px] w-full">
                                <ul class="text-[22px] leading-8 font-bold text-dark1 pl-4">
                                    <li class="singleBox-listStyle">Reorder</li>
                                    <li class="singleBox-listStyle">Replenish</li>
                                    <li class="singleBox-listStyle">Maintain Stock</li>
                                </ul>
                                <p class="text-main_purple font-medium pl-4 pt-3">
                                    Smart Budget
                                </p>
                            </div>
                        </div>
                        <div class="inventory-profit-steps py-[50px] px-[30px] rounded-[30px] bg-white">
                            <div class="grid grid-cols-12 gap-7">
                                <div class=" col-span-3">
                                    <div class="steps-wrap bg-dark7 rounded-xl p-5 h-full">
                                        <div class="single-box bg-white rounded-xl flex gap-4 items-center py-5 px-7 flex-auto border border-dark5 mb-4">
                                            <div class="">
                                                <img :src="workFlowStepIcon" alt="">
                                            </div>
                                            <div class="">
                                                <h5 class="text-main_purple font-bold text-xs leading-5 pb-1">
                                                    Step 1
                                                </h5>
                                                <p class="text-dark1 text-lg leading-6 font-medium">
                                                    Purchase
                                                </p>
                                            </div>
                                        </div>
                                        <div class="single-box bg-white rounded-xl flex gap-4 items-center py-5 px-7 flex-auto border border-dark5 mb-4">
                                            <div class="">
                                                <img :src="workFlowStepIcon" alt="">
                                            </div>
                                            <div class="">
                                                <h5 class="text-main_purple font-bold text-xs leading-5 pb-1">
                                                    Step 2
                                                </h5>
                                                <p class="text-dark1 text-lg leading-6 font-medium">
                                                    Replenish
                                                </p>
                                            </div>
                                        </div>
                                        <div class="single-box bg-white rounded-xl flex gap-4 items-center py-5 px-7 flex-auto border border-dark5 mb-4">
                                            <div class="">
                                                <img :src="workFlowStepIcon" alt="">
                                            </div>
                                            <div class="">
                                                <h5 class="text-main_purple font-bold text-xs leading-5 pb-1">
                                                    Step 3
                                                </h5>
                                                <p class="text-dark1 text-lg leading-6 font-medium">
                                                    Ship
                                                </p>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-span-9">
                                    <div class="h-full">
                                        <img :src="workflowIllustration" alt="">
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <!-- Inventory profit cart / End  -->

            <!-- /Brand carousel - Start  -->
            <section class="brand-carousel-wrapper">
                <div class="text-center">
                    <h2 class="text-5xl font-bold leading-[56px] text-white mb-5">
                        Sell where you can make money
                    </h2>
                    <p class="text-lg font-medium text-white">
                        Sync all channels right here on Inventory Ahead
                    </p>

                    <div class="brand-carousel-area py-12">
                        <div class="marquee-vertical">
                            <div class="top-slide-wrap flex gap-[30px] mb-[30px]">
                                <div v-for="brandLogo in brandLogos" class="slide-item w-[200px] h-[91px] bg-white rounded-lg grid content-center justify-center flex-shrink-0">
                                    <img :src="brandLogo.logo" :alt="brandLogo.altText" class="max-w-full w-auto">
                                </div>
                            </div>
                        </div>
                        
                        <div class="marquee-reverse">
                            <div class="top-slide-wrap flex gap-[30px]">
                                <div v-for="brandLogo in brandLogos" class="slide-item w-[200px] h-[91px] bg-white rounded-lg grid content-center justify-center flex-shrink-0">
                                    <img :src="brandLogo.logo" :alt="brandLogo.altText" class=" max-w-full w-auto">
                                </div>
                            </div>
                        </div>
                    </div>

                    <PrimaryBtn>See all integrations</PrimaryBtn>
                </div>
            </section>
            <!-- /Brand carousel - End  -->

            <!-- /Clients feedback - Start  -->
            <ClientsFeedback />
            <!-- /Clients feedback - End  -->

            <!-- /Call to action -Start  -->
            <section class="call-to-action mb-[100px]">
                <div class="wide-container mx-auto call-to-action-bg rounded-[20px] py-36">
                    <div class="container mx-auto">
                        <div class="grid grid-cols-2">
                            <div class="col-span-1">
                                <h2 class=" text-5xl font-bold leading-[56px] text-white mb-12">
                                    You do you, <br class="hidden lg:block" /> We will help you expand
                                </h2>
                                <div class="callToAction-form flex gap-[30px] flex-wrap items-center">
                                    <div>
                                        <input id="email-address" name="email" type="email" autocomplete="email" required="" class="relative block w-full appearance-none rounded-lg border-2 border-dark5 px-5 py-[15px] text-dark1 placeholder-dark3 focus:outline-none font-medium min-w-[255px]" placeholder="Email address" />
                                    </div>
                                    <div class="">
                                        <div class="inline-block">
                                            <NuxtLink to="/"
                                                class="common-btn py-[18px] px-[30px] bg-secondary text-dark1 rounded-lg flex gap-2 justify-center items-center font-semibold ">
                                                <span>
                                                    Sign up today
                                                </span>
                                                <span>
                                                    <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                        <path d="M12.0254 4.94189L17.0837 10.0002L12.0254 15.0586" stroke="#06021C" stroke-width="2" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
                                                        <path d="M2.91699 10H16.942" stroke="#06021C" stroke-width="2" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
                                                    </svg>
                                                </span>
                                            </NuxtLink>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <!-- /Call to action -End  -->
            
        </NuxtLayout>
    </div>
</template>



<style scoped>
.call-to-action-bg {
    background: url('../assets/img/call-to-action-bg.jpg') no-repeat;
    background-size: cover;
    background-position: center;
}

.top-slide-wrap {
    animation: animated-slide 60s linear infinite;
}
@keyframes animated-slide {
    0% {
        transform: translateX(0);
    }

    100% {
        transform: translateX(calc(-230px * 9));
    }
}

.marquee-reverse .top-slide-wrap {
    animation-direction: reverse;
    animation-delay: -3s;
}


.clients-feedback-wrapper {
    background: linear-gradient(180deg, #F9F8FC 0%, rgba(249, 248, 252, 0) 100%);
}

.profit-bg-shape {
    background: url('../assets/img/inventory-profit-shape.svg'), linear-gradient(180deg, #ffffff 0%, rgba(255, 255, 255, 1) 100%);
    background-repeat: no-repeat;
    background-position-x: 90%, center;
    background-position-y: 70%, center;
}

.steps-wrap {
    background: url('../assets/img/work-flow-step-bg-shape.png'), linear-gradient(180deg, #F9F8FC 0%, rgba(249, 248, 252, 1) 100%);
    background-repeat: no-repeat;
    background-position-x: 50%, center;
    background-position-y: 95%, center;
    background-size: 80%, 100%;
}


</style>