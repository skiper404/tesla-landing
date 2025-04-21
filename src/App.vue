<script setup>
import Logo from '@/Logo.vue';
import { ChevronDownIcon } from '@heroicons/vue/24/solid';
import { ChevronLeftIcon } from '@heroicons/vue/16/solid';
import { XMarkIcon } from '@heroicons/vue/16/solid';
import { GlobeAmericasIcon } from '@heroicons/vue/24/outline';
</script>

<template>
  <div>
    <!-- <div class="fixed z-20 inset-0 backdrop-blur-xs bg-[rgba(0,0,0,0.3)]">
      <div class="absolute right-0 h-screen w-[300px] bg-white">
        <div class="flex justify-between items-center p-2">
          <button class="flex items-center p-2 hover:bg-gray-500/50 rounded-full"><ChevronLeftIcon class="size-6" /> <span> Back </span></button>
          <button class="flex items-center justify-center cursor-pointer rounded-full transition diration-300 hover:bg-gray-500/50 p-2">
            <XMarkIcon class="size-6" />
          </button>
        </div>
        <ul class="py-1 px-10 flex flex-col gap-2 text-xl font-extralight">
          <li>
            <a href="#" class="inline-block w-full transition duration-300 hover:bg-orange-300/20 px-4 py-2 rounded-xl"
              ><span>Existing Inventory</span></a
            >
          </li>
          <li>
            <a href="#" class="inline-block w-full transition duration-300 hover:bg-orange-300/20 px-4 py-2 rounded-xl"
              ><span>Used Inventory</span></a
            >
          </li>
          <li>
            <a href="#" class="inline-block w-full transition duration-300 hover:bg-orange-300/20 px-4 py-2 rounded-xl"><span>Trade-In</span></a>
          </li>
          <li>
            <a href="#" class="inline-block w-full transition duration-300 hover:bg-orange-300/20 px-4 py-2 rounded-xl"><span>Test Drive</span></a>
          </li>
          <li>
            <a href="#" class="inline-block w-full transition duration-300 hover:bg-orange-300/20 px-4 py-2 rounded-xl"><span>Cybertruck</span></a>
          </li>
          <li>
            <a href="#" class="inline-block w-full transition duration-300 hover:bg-orange-300/20 px-4 py-2 rounded-xl"><span>Roadster</span></a>
          </li>
          <li>
            <a href="#" class="inline-block w-full transition duration-300 hover:bg-orange-300/20 px-4 py-2 rounded-xl"><span>Semi</span></a>
          </li>
          <li>
            <a href="#" class="inline-block w-full transition duration-300 hover:bg-orange-300/20 px-4 py-2 rounded-xl"><span>Charging</span></a>
          </li>
          <li>
            <a href="#" class="inline-block w-full transition duration-300 hover:bg-orange-300/20 px-4 py-2 rounded-xl"><span>Powerwall</span></a>
          </li>
          <li>
            <a href="#" class="inline-block w-full transition duration-300 hover:bg-orange-300/20 px-4 py-2 rounded-xl"
              ><span>Commercial Energy</span></a
            >
          </li>
          <li>
            <a href="#" class="inline-block w-full transition duration-300 hover:bg-orange-300/20 px-4 py-2 rounded-xl"><span>Utilities</span></a>
          </li>
          <li>
            <a href="#" class="inline-block w-full transition duration-300 hover:bg-orange-300/20 px-4 py-2 rounded-xl"><span>Find Us</span></a>
          </li>
          <li>
            <a href="#" class="inline-block w-full transition duration-300 hover:bg-orange-300/20 px-4 py-2 rounded-xl"><span>Support</span></a>
          </li>
          <li>
            <a href="#" class="inline-block w-full transition duration-300 hover:bg-orange-300/20 px-4 py-2 rounded-xl"
              ><span>Invester Relations</span></a
            >
          </li>
          <li>
            <a href="#" class="flex items-center gap-2 w-full transition duration-300 hover:bg-orange-300/20 px-4 py-2 rounded-xl">
              <GlobeAmericasIcon class="size-10" />
              <span class="flex flex-col"> <span>United States</span> <span>English</span></span>
            </a>
          </li>
        </ul>
      </div>
    </div> -->
    <header class="flex z-10 items-center justify-between gap-5 w-full px-2 sm:px-10 fixed inset-0 h-20">
      <div class="flex items-center px-2">
        <a href="#">
          <Logo class="w-30 h-6" />
        </a>
      </div>
      <div class="sm:hidden hover:bg-gray-500/50 transition duration-300 rounded-xl ransition px-3 m-1">
        <span class="t">Menu</span>
      </div>
      <ul class="xl:flex gap-3 items-center justify-between font-light px-2 hidden">
        <li class="transition duration-300 rounded-full hover:bg-gray-500/50 px-3">
          <span class="m-1"> Model S </span>
        </li>
        <li class="transition duration-300 rounded-full hover:bg-gray-500/50 px-3">
          <span class="m-1"> Model 3 </span>
        </li>
        <li class="transition duration-300 rounded-full hover:bg-gray-500/50 px-3">
          <span class="m-1"> Model X </span>
        </li>
        <li class="transition duration-300 rounded-full hover:bg-gray-500/50 px-3">
          <span class="m-1"> Model Y </span>
        </li>
        <li class="transition duration-300 rounded-full hover:bg-gray-500/50 px-3">
          <span class="m-1"> Solar Panels </span>
        </li>
        <li class="transition duration-300 rounded-full hover:bg-gray-500/50 px-3">
          <span class="m-1"> Solar Roof </span>
        </li>
      </ul>
      <ul class="sm:flex items-center gap-3 font-light hidden">
        <li class="transition duration-300 rounded-full hover:bg-gray-500/50 px-3">
          <span class="m-1"> Shop </span>
        </li>
        <li class="transition duration-300 rounded-full hover:bg-gray-500/50 px-3">
          <span class="m-1"> Account </span>
        </li>
        <li class="transition duration-300 rounded-full hover:bg-gray-500/50 px-3">
          <span class="m-1"> Menu </span>
        </li>
      </ul>
    </header>
    <main
      class="bg-cover bg-center bg-no-repeat bg-[url('./img/mobile-model-s.jpeg')] sm:bg-[url('/img/model-s.jpeg')] flex flex-col items-center justify-between h-screen py-40"
    >
      <div class="text-center">
        <h1 class="text-6xl font-light tracking-wide">Model S</h1>
        <h2 class="font-light tracking-wider">
          Order online for
          <a href="#" class="border-b hover:border-b-[2px]">Touchless Delivery</a>
        </h2>
      </div>
      <div class="relative flex items-center justify-center gap-5 flex-col sm:flex-row">
        <a href="#" class="uppercase bg-gray-700/80 text-center w-[260px] py-2 rounded-full text-white text-xs font-light tracking-widest">
          Custom Order
        </a>
        <a href="#" class="uppercase bg-gray-100/80 text-center w-[260px] py-2 rounded-full text-xs font-light tracking-widest">
          Exiting Inventory
        </a>
        <ChevronDownIcon class="size-16 absolute -bottom-40 animate-bounce" />
      </div>
    </main>
    <main
      class="bg-cover bg-center bg-no-repeat bg-[url('./img/mobile-model-3.jpeg')] sm:bg-[url('/img/model-3.jpeg')] flex flex-col items-center justify-between h-screen py-40"
    >
      <div class="text-center">
        <h1 class="text-6xl font-light tracking-wide">Model 3</h1>
        <h2 class="font-light tracking-wider">
          Order online for
          <a href="#" class="border-b hover:border-b-[2px]">Touchless Delivery</a>
        </h2>
      </div>
      <div class="relative flex items-center justify-center gap-5 flex-col sm:flex-row">
        <a href="#" class="uppercase bg-gray-700/80 w-[240px] text-center py-2 rounded-full text-white text-xs font-light tracking-widest"
          >Custom Order</a
        >
        <a href="#" class="uppercase bg-gray-100/80 w-[240px] text-center py-2 rounded-full text-xs font-light tracking-widest">Exiting Inventory</a>
        <ChevronDownIcon class="size-16 absolute -bottom-40 animate-bounce" />
      </div>
    </main>
    <main
      class="bg-cover bg-center bg-no-repeat bg-[url('./img/mobile-model-y.jpeg')] sm:bg-[url('/img/model-y.jpeg')] flex flex-col items-center justify-between h-screen py-50"
    >
      <div class="text-center">
        <h1 class="text-6xl font-light tracking-wide">Model Y</h1>
        <h2 class="font-light tracking-wider">
          Order online for
          <a href="#" class="border-b hover:border-b-[2px]">Touchless Delivery</a>
        </h2>
      </div>
      <div class="relative flex items-center justify-center gap-5 flex-col sm:flex-row">
        <a href="#" class="uppercase bg-gray-700/80 text-center w-[260px] py-2 rounded-full text-white text-xs font-light tracking-widest">
          Custom Order
        </a>
        <a href="#" class="uppercase bg-gray-100/80 text-center w-[260px] py-2 rounded-full text-xs font-light tracking-widest">
          Exiting Inventory
        </a>
        <ChevronDownIcon class="size-16 absolute -bottom-40 animate-bounce" />
      </div>
    </main>
    <main
      class="bg-cover bg-center bg-no-repeat bg-[url('./img/mobile-model-x.jpeg')] sm:bg-[url('/img/model-x.jpeg')] flex flex-col items-center justify-between h-screen py-40"
    >
      <div class="text-center">
        <h1 class="text-6xl font-light tracking-wide">Model X</h1>
        <h2 class="font-light tracking-wider">
          Order online for
          <a href="#" class="border-b hover:border-b-[2px]">Touchless Delivery</a>
        </h2>
      </div>
      <div class="relative flex items-center justify-center gap-5 flex-col sm:flex-row">
        <a href="#" class="uppercase bg-gray-700/80 text-center w-[260px] py-2 rounded-full text-white text-xs font-light tracking-widest">
          Custom Order
        </a>
        <a href="#" class="uppercase bg-gray-100/80 text-center w-[260px] py-2 rounded-full text-xs font-light tracking-widest">
          Exiting Inventory
        </a>
        <ChevronDownIcon class="size-16 absolute -bottom-40 animate-bounce" />
      </div>
    </main>
    <main
      class="bg-cover bg-center bg-no-repeat bg-[url('./img/mobile-solar-roof.jpeg')] sm:bg-[url('/img/solar-roof.jpeg')] flex flex-col items-center justify-between h-screen py-40"
    >
      <div class="text-center">
        <h1 class="text-6xl font-light tracking-wide">Solar Roof</h1>
        <h2 class="font-light tracking-wider my-2">Produce Clean Energy From Your Roof</h2>
      </div>
      <div class="relative flex items-center justify-center gap-5 flex-col sm:flex-row">
        <a href="#" class="uppercase bg-gray-700/80 text-center w-[260px] py-2 rounded-full text-white text-xs font-light tracking-widest">
          Order now
        </a>
        <a href="#" class="uppercase bg-gray-100/80 text-center w-[260px] py-2 rounded-full text-xs font-light tracking-widest"> Learn more </a>
        <ChevronDownIcon class="size-16 absolute -bottom-40 animate-bounce" />
      </div>
    </main>
    <main
      class="bg-cover bg-center bg-no-repeat bg-[url('./img/mobile-solar-panels.jpeg')] sm:bg-[url('/img/solar-panels.jpeg')] flex flex-col items-center justify-between h-screen py-40"
    >
      <div class="text-center">
        <h1 class="text-6xl font-light tracking-wide">Solar Panels</h1>
        <h2 class="font-light tracking-wider my-2">Lowest Cost Solar Panels in America</h2>
      </div>
      <div class="relative flex items-center justify-center gap-5 flex-col sm:flex-row">
        <a href="#" class="uppercase bg-gray-700/80 text-center w-[260px] py-2 rounded-full text-white text-xs font-light tracking-widest">
          Order now
        </a>
        <a href="#" class="uppercase bg-gray-100/80 text-center w-[260px] py-2 rounded-full text-xs font-light tracking-widest"> Learn more </a>
        <ChevronDownIcon class="size-16 absolute -bottom-40 animate-bounce" />
      </div>
    </main>
    <main
      class="relative bg-cover bg-center bg-no-repeat bg-[url('./img/mobile-accessories.jpeg')] sm:bg-[url('/img/accessories.jpeg')] flex flex-col items-center justify-between h-screen py-40"
    >
      <div class="text-center">
        <h1 class="text-6xl font-light tracking-wide">Accessories</h1>
      </div>
      <div class="relative flex items-center justify-center gap-5 flex-col sm:flex-row">
        <a href="#" class="uppercase bg-gray-900 text-center w-[260px] py-2 rounded-full text-white text-xs font-light tracking-widest"> Shop now </a>
      </div>
      <footer class="absolute bottom-0 w-full flex items-center justify-center font-medium tracking-wider">
        <ul class="flex items-center flex-col sm:flex-row sm:gap-5">
          <li class="pb-4"><a href="#"> Tesla &copy; 2022 </a></li>
          <li class="pb-4"><a href="#"> Privacy &amp; Legal </a></li>
          <li class="pb-4 hidden sm:inline"><a href="#"> Contact </a></li>
          <li class="pb-4"><a href="#"> Careers </a></li>
          <li class="pb-4 hidden sm:inline"><a href="#"> Engage </a></li>
          <li class="pb-4 hidden sm:inline"><a href="#"> Location </a></li>
        </ul>
      </footer>
    </main>
  </div>
</template>
