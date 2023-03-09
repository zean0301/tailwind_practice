<script setup>
  import HelloWorld from './components/HelloWorld.vue'
  import TheWelcome from './components/TheWelcome.vue'
</script>

<template>

  <div class="w-32 h-32">
    <div class="my-4 mx-4 border-[0.8px] py-8 pl-8 pr-4 rounded-lg border-black">
      <div class="my-4 mx-4">

      </div>
    </div>
  </div>

  <div class="bg-emerald-300 w-16 flex justify-center">
    <h2 class="text-rose-600 ">
      text
    </h2>
  </div>
  <br>
  <button class="w-32 h-8 bg-cyan-500 rounded-full text-white font-bold hover:bg-sky-700">
    Save Change
  </button>
  <br>
  <br>
  <button class="w-32 h-8 bg-cyan-500 rounded-full text-white font-bold bg-violet-500 hover:bg-violet-600 active:bg-violet-700 focus:outline-none focus:ring focus:ring-rose-600 ">
    button
  </button>
  <br>
  <br>
  <div class="flex justify-center">
    <button class="bg-orange-400 md:hidden w-32 h-8 bg-cyan-500 font-bold">
      button
    </button>
    <button class="hidden bg-lime-400 xl:hidden lg:hidden md:block sm:hidden w-32 h-8 bg-cyan-500 font-bold">
      button
    </button> 
    <button class="hidden bg-cyan-200  lg:block xl:hidden w-32 h-8 bg-cyan-500 font-bold">
      button
    </button>
    <button class="hidden bg-sky-400 xl:block w-32 h-8 bg-cyan-500 font-bold">
      button
    </button>
  </div>

</template>