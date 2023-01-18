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
                        <NuxtLink to="/">Home</NuxtLink>
                        <NuxtLink to="/features">Features</NuxtLink>
                        <NuxtLink to="/company">Company</NuxtLink>
                        <NuxtLink to="/integrations">Integrations</NuxtLink>
                        <NuxtLink to="/pricing-page">Pricing</NuxtLink>
                        <NuxtLink to="/registration-new">Help Center</NuxtLink>
                    </div>
                    <div class="login-btn text-white flex gap-8 items-center">
                        <NuxtLink to="/login-new">Login</NuxtLink>
                        <SecondaryBtn>Try for Free</SecondaryBtn>
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