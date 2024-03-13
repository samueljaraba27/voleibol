<template>
    <div class="snap-center">
        <nav class="fixed flex flex-col justify-center items-start bg-black h-[120px] top-0">
            <div class="flex justify-between sm:justify-around items-center bg-zinc-800 w-[100vw] h-[60px]">
                <img class="w-10 h-10" src="../assets/logo_.png" alt="">
                <article class="text-white text-xs hidden sm:block">INICIO</article>
                <article class="text-white text-xs hidden sm:block">SOBRE NOSOTROS</article>
                <article class="text-white text-xs hidden sm:block">CONTACTANOS</article>
                <article class="text-white text-xs hidden sm:block">TORNEOS</article>
                <span class="cursor-pointer hidden sm:block">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2"
                        stroke="white" class="w-6 h-6">
                        <path stroke-linecap="round" stroke-linejoin="round"
                            d="m21 21-5.197-5.197m0 0A7.5 7.5 0 1 0 5.196 5.196a7.5 7.5 0 0 0 10.607 10.607Z" />
                    </svg>
                </span>
                <span class="sm:hidden block">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2"
                        stroke="white" class="w-6 h-6">
                        <path stroke-linecap="round" stroke-linejoin="round"
                            d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
                    </svg>
                </span>
            </div>
            <MoreComponent />
        </nav>
    </div>
</template>
<script>
import MoreComponent from './MoreComponent.vue';
export default {
    name: 'NavComponent',
    components: {
        MoreComponent
    },
    data() {

    }
}
</script>