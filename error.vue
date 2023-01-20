<template>
    <div class="container mx-auto">

        <Head>
            <Title>404 error | Inventory Ahead Dashboard</Title>
            <Meta name="description" content="Inventory Ahead Dashboard" />
        </Head>
        <div class=" flex justify-center items-center h-screen">
            <div class=" basis-2/5 text-center">
                <div class=" mb-10">
                    <img src="./assets/img/404.svg" alt="404 image" class="">
                </div>
                <!-- <h2 class=" text-8xl text-main_purple font-bold mb-8">
                    {{ error.statusCode }}
                </h2> -->

                

                <div class="inline-block">
                    <NuxtLink to="/"
                        class="common-btn py-[17px] px-[29px] bg-main_purple text-white border border-main_purple rounded-lg flex gap-2 justify-center items-center font-semibold hover:bg-transparent hover:text-main_purple transition-colors duration-300 ease-in-out">
                        <span>
                            Back to home
                        </span>
                        <span>
                            <!-- <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path class="icon-hover" d="M12.0254 4.94165L17.0837 9.99998L12.0254 15.0583" stroke="white" stroke-width="2"
                                    stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round" />
                                <path class="icon-hover" d="M2.91699 10H16.942" stroke="white" stroke-width="2" stroke-miterlimit="10"
                                    stroke-linecap="round" stroke-linejoin="round" />
                            </svg> -->

                            <svg width="17" height="18" viewBox="0 0 17 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path class="icon-hover" d="M6.37533 16.0833H10.6253C14.167 16.0833 15.5837 14.6666 15.5837 11.125V6.87496C15.5837 3.33329 14.167 1.91663 10.6253 1.91663H6.37533C2.83366 1.91663 1.41699 3.33329 1.41699 6.87496V11.125C1.41699 14.6666 2.83366 16.0833 6.37533 16.0833Z" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                                <path class="icon-hover" d="M6.37487 11.3941H9.85987C11.064 11.3941 12.0415 10.4166 12.0415 9.21243C12.0415 8.00826 11.064 7.03076 9.85987 7.03076H5.06445" stroke="white" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
                            <path class="icon-hover" d="M6.07009 8.12871L4.95801 7.00954L6.07009 5.89746" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>

                        </span>
                    </NuxtLink>
                </div>

            </div>
        </div>
    </div>
</template>


<script setup>
defineProps(['error'])
</script>

<style scoped>

</style>