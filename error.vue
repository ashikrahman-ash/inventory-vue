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

                <NuxtLink to="/" class="">
                    <PrimaryBtn>Back to home</PrimaryBtn>
                </NuxtLink>


            </div>
        </div>
    </div>
</template>


<script setup>
defineProps(['error'])
</script>

<style scoped>

</style>