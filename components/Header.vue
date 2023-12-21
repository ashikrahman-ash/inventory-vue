<template>
    <header>
        <div class="header-wrap grid content-center z-20 relative">
            <div class="wide-container mx-auto">
                <div class="flex">
                    <div class="logo flex items-center">
                        <NuxtLink to="/">
                            <img src="../assets/img/logo-white.svg" alt="">
                        </NuxtLink>
                    </div>
                    <div class="menu-bar text-white flex-auto flex items-center justify-center gap-8">
                        <NuxtLink to="/" class=" hover:text-secondary transition-all duration-500 relative before:absolute before:content-[''] before:bg-secondary before:w-2 before:h-[5px] before:left-[50%] before:-translate-x-1 before:transition-all before:duration-200 before:rounded-b-[20px] before:-top-[48px] hover:before:-top-[42px]">Home</NuxtLink>
                        <NuxtLink to="/features" class=" hover:text-secondary transition-all duration-500 relative before:absolute before:content-[''] before:bg-secondary before:w-2 before:h-[5px] before:left-[50%] before:-translate-x-1 before:transition-all before:duration-200 before:rounded-b-[20px] before:-top-[48px] hover:before:-top-[42px]">Features</NuxtLink>
                        <NuxtLink to="/company" class=" hover:text-secondary transition-all duration-500 relative before:absolute before:content-[''] before:bg-secondary before:w-2 before:h-[5px] before:left-[50%] before:-translate-x-1 before:transition-all before:duration-200 before:rounded-b-[20px] before:-top-[48px] hover:before:-top-[42px]">Company</NuxtLink>
                        <NuxtLink to="/integrations" class=" hover:text-secondary transition-all duration-500 relative before:absolute before:content-[''] before:bg-secondary before:w-2 before:h-[5px] before:left-[50%] before:-translate-x-1 before:transition-all before:duration-200 before:rounded-b-[20px] before:-top-[48px] hover:before:-top-[42px]">Integrations</NuxtLink>
                        <NuxtLink to="/pricing-page" class=" hover:text-secondary transition-all duration-500 relative before:absolute before:content-[''] before:bg-secondary before:w-2 before:h-[5px] before:left-[50%] before:-translate-x-1 before:transition-all before:duration-200 before:rounded-b-[20px] before:-top-[48px] hover:before:-top-[42px]">Pricing</NuxtLink>
                        <NuxtLink to="/registration-new" class=" hover:text-secondary transition-all duration-500 relative before:absolute before:content-[''] before:bg-secondary before:w-2 before:h-[5px] before:left-[50%] before:-translate-x-1 before:transition-all before:duration-200 before:rounded-b-[20px] before:-top-[48px] hover:before:-top-[42px]">Help Center</NuxtLink>
                    </div>
                    <div class="login-btn text-white flex gap-8 items-center">
                        <NuxtLink to="/login-new">Login</NuxtLink>
                        <SecondaryBtn>
                            <NuxtLink to="/registration-new">Try for Free</NuxtLink>
                        </SecondaryBtn>
                    </div>
                </div>
            </div>
        </div>
    </header>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    .header-wrap {
        background: linear-gradient(180deg, rgba(11, 1, 64, 0.6) 0%, rgba(11, 1, 64, 0) 100%);
        height: 108px;
        margin-bottom: -108px;
    }
</style>