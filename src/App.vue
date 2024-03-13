<template>
  <div class="absolute bg-black h-[100vh] -z-10 top-0">
    <img src="./assets/baner.webp" class="w-[100vw] h-full object-cover blur-md" alt="">
  </div>
  <OctavosComponent />
  <div class="hidden relative">
    <div class="min-w-[1030px] overflow-x-auto">
      <div
        class="absolute flex flex-col gap-4 h-[40%] font-mono text-black text-sm text-center font-bold leading-6 bg-stripes-pink rounded-lg left-20 top-[30%] w-[100px]">
        <div class="p-4 rounded-lg shadow-lg bg-[#D9D9D9]"><i>Equipo</i></div>
        <div class="p-4 rounded-lg shadow-lg bg-[#D9D9D9]"><i>Equipo</i></div>
        <div class="p-4 rounded-lg shadow-lg bg-[#D9D9D9]"><i>Equipo</i></div>
        <div class="p-4 rounded-lg shadow-lg bg-[#D9D9D9]"><i>Equipo</i></div>
      </div>
      <div
        class="absolute flex justify-around h-[40%] flex-col gap-4 font-mono text-black text-sm text-center font-bold leading-6 bg-stripes-pink rounded-lg left-60 top-[30%] w-[100px]">
        <div class="p-4 rounded-lg shadow-lg bg-[#D9D9D9]"><i>Equipo</i></div>
        <div class="p-4 rounded-lg shadow-lg bg-[#D9D9D9]"><i>Equipo</i></div>
      </div>
      <div
        class="absolute flex justify-around h-[40%] flex-col gap-4 font-mono text-black text-sm text-center font-bold leading-6 bg-stripes-pink rounded-lg left-96 top-[30%] w-[100px]">
        <div class="p-4 rounded-lg shadow-lg bg-[#D9D9D9]"><i>Equipo</i></div>
      </div>
      <img src="./assets/copa.png" class="absolute h-30 w-24 top-[40%] left-[45%]" alt="">
      <div
        class="absolute flex justify-around h-[40%] flex-col gap-4 font-mono text-black text-sm text-center font-bold leading-6 bg-stripes-pink rounded-lg right-96 top-[30%] w-[100px]">
        <div class="p-4 rounded-lg shadow-lg bg-[#D9D9D9]"><i>Equipo</i></div>
      </div>
      <div
        class="absolute flex justify-around h-[40%] flex-col gap-4 font-mono text-black text-sm text-center font-bold leading-6 bg-stripes-pink rounded-lg right-60 top-[30%] w-[100px]">
        <div class="p-4 rounded-lg shadow-lg bg-[#D9D9D9]"><i>Equipo</i></div>
        <div class="p-4 rounded-lg shadow-lg bg-[#D9D9D9]"><i>Equipo</i></div>
      </div>
      <div
        class="absolute flex flex-col gap-4 font-mono text-black text-sm text-center font-bold leading-6 bg-stripes-pink rounded-lg right-20 top-[30%] w-[100px]">
        <div class="p-4 rounded-lg shadow-lg bg-[#D9D9D9]"><i>Equipo</i></div>
        <div class="p-4 rounded-lg shadow-lg bg-[#D9D9D9]"><i>Equipo</i></div>
        <div class="p-4 rounded-lg shadow-lg bg-[#D9D9D9]"><i>Equipo</i></div>
        <div class="p-4 rounded-lg shadow-lg bg-[#D9D9D9]"><i>Equipo</i></div>
      </div>
    </div>
  </div>
  <NavComponent />
  <div class="h-[calc(100vh-16vh)] bg-black snap-center p-10">
    <div
      class="grid grid-cols-2 gap-4 font-mono text-white text-sm text-center font-bold leading-6 bg-stripes-pink rounded-lg">
      <div class="p-4 rounded-lg shadow-lg bg-pink-500">01</div>
      <div class="p-4 rounded-lg shadow-lg bg-pink-500">02</div>
    </div>
  </div>
</template>
<script>
import OctavosComponent from './components/OctavosComponent.vue';
import NavComponent from './components/NavComponent.vue';
export default {
  name: 'App',
  components: {
    OctavosComponent,
    NavComponent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>./components/NavComponent.vue
