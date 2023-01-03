<script>
import serviceIcon1 from '../assets/img/services-icon-1.png'
import serviceIcon2 from '../assets/img/services-icon-2.png'
import serviceIcon3 from '../assets/img/services-icon-3.png'
import serviceIcon4 from '../assets/img/services-icon-4.png'
import serviceIcon5 from '../assets/img/services-icon-5.png'
import serviceIcon6 from '../assets/img/services-icon-6.png'

export default {
    data() {
        return {
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
                },
            ]
        }
    }
}
</script>

<template>
        <NuxtLayout>
            <HomeHero />
            <div class="container mx-auto my-28">
                <div class="grid grid-cols-3 gap-7">
                    <div v-for="service in services" key="id" class="service-item pt-10 px-8 pb-8 bg-dark7 rounded-xl border-2 border-dark7 hover:border-dark5 hover:bg-white transition-colors duration-200">
                        <div class="service-icon mb-8">
                            <img :src="service.icon" alt="" class=" max-w-full">
                        </div>
                        <h3 class="service-heading font-semibold text-dark1 text-4xl mb-5">
                            {{ service.title }}
                        </h3>
                        <p class=" text-dark2 text-lg">
                            {{ service.content }}
                        </p>
                    </div>
                </div>
            </div>
        </NuxtLayout>
</template>

<style scoped>

</style>