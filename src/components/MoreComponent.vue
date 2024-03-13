<template>
    <div
        :class="expanded ? 'absolute flex justify-center items-end top-[120px] h-[500px] bg-[#D9D9D9] w-[100%] rounded-b-[20px] z-10 transition-all duration-300' : 'absolute flex justify-center items-end top-[120px] h-10 bg-[#D9D9D9] w-[100%] rounded-b-[20px] z-10 transition-all duration-300'">
        <div class="flex flex-col justify-center items-center w-full cursor-pointer" @click="() => expanded = !expanded">
            <article class="text-black font-bold text-xs" v-text="expanded ? 'OCULTAR' : 'MOSTRAR MAS'"></article>
            <span :class="{ 'rotate-180': expanded, 'rotate-0': !expanded }">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="3"
                    stroke="currentColor" class="w-6 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
                </svg>
            </span>
        </div>
    </div>
</template>
<script>
export default {
    name: 'MoreComponent',
    components: {
    },
    data() {
        return {
            expanded: false,
        }
    },
    methods: {
        showMore() {
            this.expanded = !this.expanded;
        }
    }
}
</script>