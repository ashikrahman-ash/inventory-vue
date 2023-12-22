<template>
    <div class="inline-block">
        <NuxtLink to="/"
            class="text-base md:text-lg py-3 md:py-[17px] px-7 bg-main_purple text-white border border-main_purple rounded-lg gap-2 justify-center items-center font-semibold hover:bg-secondary hover:text-dark1 hover:border-secondary transition-all duration-300 ease-in-out group inline-flex h-[50px] min-w-[205px]">
            <span>
                <slot />
            </span>
            <span>
                <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path class="icon-hover group-hover:stroke-dark1 group-hover:transition-all group-hover:duration-300" d="M12.0254 4.94165L17.0837 9.99998L12.0254 15.0583" stroke="white" stroke-width="2"
                        stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round" />
                    <path class="icon-hover group-hover:stroke-dark1 group-hover:transition-all group-hover:duration-300" d="M2.91699 10H16.942" stroke="white" stroke-width="2" stroke-miterlimit="10"
                        stroke-linecap="round" stroke-linejoin="round" />
                </svg>
            </span>
        </NuxtLink>
    </div>
</template>



