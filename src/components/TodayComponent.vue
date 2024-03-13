<template>
    <div v-if="visible">
        <div
            :class="mostrar ? 'scroll rounded-xl overflow-auto p-8 h-full transition-all duration-700 translate-y-0' : 'rounded-xl overflow-auto p-8 h-[100%] transition-all duration-700 translate-y-[50px] opacity-0'">
            <div class="flex flex-row h-full gap-4 font-mono text-white text-sm font-bold leading-6 overflow-x">
                <div class="min-w-80 h-60 rounded-[25px] flex items-center justify-center bg-white shadow-lg">01
                </div>
                <div class="min-w-80 h-60 rounded-[25px] flex items-center justify-center bg-white shadow-lg">01
                </div>
                <div class="min-w-80 h-60 rounded-[25px] flex items-center justify-center bg-white shadow-lg">01
                </div>
                <div class="min-w-80 h-60 rounded-[25px] flex items-center justify-center bg-white shadow-lg">01
                </div>
                <div class="min-w-80 h-60 rounded-[25px] flex items-center justify-center bg-white shadow-lg">01
                </div>
                <div class="min-w-80 h-60 rounded-[25px] flex items-center justify-center bg-white shadow-lg">01
                </div>
                <div class="min-w-80 h-60 rounded-[25px] flex items-center justify-center bg-white shadow-lg">01
                </div>
                <div class="min-w-80 h-60 rounded-[25px] flex items-center justify-center bg-white shadow-lg">01
                </div>
                <div class="min-w-80 h-60 rounded-[25px] flex items-center justify-center bg-white shadow-lg">01
                </div>
                <div class="min-w-80 h-60 rounded-[25px] flex items-center justify-center bg-white shadow-lg">01
                </div>
                <div class="min-w-80 h-60 rounded-[25px] flex items-center justify-center bg-white shadow-lg">01
                </div>
                <div class="min-w-80 h-60 rounded-[25px] flex items-center justify-center bg-white shadow-lg">01
                </div>
                <div class="min-w-80 h-60 rounded-[25px] flex items-center justify-center bg-white shadow-lg">01
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: "TodayComponent",
    props: {
        visible: Boolean
    },
    data() {
        return {
            mostrar: this.$props.visible
        }
    },
    watch: {
        visible: function (newValue) {
            setTimeout(() => {
                this.mostrar = newValue;
            }, 50);
        }
    }

}
</script>