<template>
    <div class="flex justify-between items-center h-[100vh] gap-20 overflow-auto scroll relative">
        <div class="flex flex-col items-start pl-20 gap-10">
            <template v-for="(equipo, index) in octavosDeFinal" :key="index">
                <span class="text-white  p-4 border rounded-xl relative">
                    {{ equipo.equipoLocal }}
                </span>
            </template>
        </div>

        <div class="flex flex-col items-center gap-10">
            <span class="text-white  p-4 border rounded-xl relative">
                Equipo
            </span>
            <span class="text-white  p-4 border rounded-xl invisible relative">
                Equipo
            </span>
            <span class="text-white  p-4 border rounded-xl relative">
                Equipo
            </span>
        </div>

        <div class="flex flex-col items-center gap-10">
            <span class="text-white  p-4 border rounded-xl relative">
                Equipo
            </span>
        </div>
        <img src="../assets/copa.png" class="w-20 h-20" alt="trofeo de ganador">
        <div class="flex flex-col items-center gap-10">
            <span class="text-white  p-4 border rounded-xl relative">
                Equipo
            </span>
        </div>

        <div class="flex flex-col items-center gap-10">
            <span class="text-white  p-4 border rounded-xl relative">
                Equipo
            </span>
            <span class="text-white  p-4 border rounded-xl invisible relative">
                Equipo
            </span>
            <span class="text-white  p-4 border rounded-xl relative">
                Equipo
            </span>
        </div>

        <div class="flex flex-col items-end pr-20 gap-10">
            <template v-for="(equipo, index) in octavosDeFinal" :key="index">
                <span class="text-white  p-4 border rounded-xl relative">
                    {{ equipo.equipoLocal }}
                </span>
            </template>
        </div>
    </div>
</template>
<style scoped>
.no-zoom {
    zoom: 1;
}
</style>

<script>
export default {
    name: 'OctavosComponent',
    components: {
    },
    data() {
        return {
            octavosDeFinal: [
                { equipoLocal: 'Equipo' },
                { equipoLocal: 'Equipo' },
                { equipoLocal: 'Equipo' },
                { equipoLocal: 'Equipo' },
            ],
        }
    }
}
</script>