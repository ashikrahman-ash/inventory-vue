<template>
    <div class="inline-block">
        <NuxtLink to="/"
            class="common-btn py-[17px] px-[29px] bg-main_purple text-white border border-main_purple rounded-lg flex gap-2 justify-center items-center font-semibold hover:bg-transparent hover:text-main_purple transition-colors duration-300 ease-in-out">
            <span>
                <slot />
            </span>
            <span>
                <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path class="icon-hover" d="M12.0254 4.94165L17.0837 9.99998L12.0254 15.0583" stroke="white" stroke-width="2"
                        stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round" />
                    <path class="icon-hover" d="M2.91699 10H16.942" stroke="white" stroke-width="2" stroke-miterlimit="10"
                        stroke-linecap="round" stroke-linejoin="round" />
                </svg>
            </span>
        </NuxtLink>
    </div>
</template>

<script>
export default {

}
</script>


<style>
.icon-hover {
    transition: all .2s linear;
}
.common-btn:hover .icon-hover {
    stroke: #2E00FF;
}

</style>