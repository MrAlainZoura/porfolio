<template>
  
    <div class="mx-auto max-w-6xl shadow-lg  bg-transparent border-none" style="box-shadow: 0 4px 30px rgba(17, 24, 39, 0.7);">
    <div class="relative bg-transparent border-none isolate overflow-hidden sm:rounded-3xl sm:px-16 md:pt-24 lg:flex lg:gap-x-20 lg:px-24 lg:pt-0">
      <svg viewBox="0 0 1024 1024" class="absolute top-1/2 left-1/2 -z-10 size-[64rem] -translate-y-1/2 [mask-image:radial-gradient(closest-side,white,transparent)] sm:left-full sm:-ml-80 lg:left-1/2 lg:ml-0 lg:-translate-x-1/2 lg:translate-y-0" aria-hidden="true">
        <circle cx="512" cy="512" r="512" fill="url(#759c1415-0410-454c-8f7c-9a820de03641)" fill-opacity="0.7" />
        <defs>
          <radialGradient id="759c1415-0410-454c-8f7c-9a820de03641">
            <stop stop-color="#7775D6" />
            <stop offset="1" stop-color="#E935C1" />
          </radialGradient>
        </defs>
      </svg>
      <div class="mx-auto max-w-full w-4/5 text-center lg:mx-0 lg:flex-auto lg:py-10 lg:text-left">
        <label for="" class="text-sm/6 font-semibold text-yellow-500">Hi, I'm </label>
         <h2 class="text-3xl font-semibold tracking-tight text-balance text-white sm:text-4xl">Alain TSHIYANZE</h2>
        <p class="mt-6 text-lg/8 text-pretty text-gray-300 text-justify">
            I create things for the web.
            I build applications, websites, and other digital experiences that live on the internet.
            My focus is on using the latest web technologies and frameworks to deliver high-quality, user-friendly products. Whether it's a simple landing page or a complex web application,
            I enjoy the process of taking an idea and turning it into a tangible, functional reality on the web.
        </p>
        <div class="mt-10 flex items-center justify-center gap-x-6 lg:justify-start">
          <a href="#" class="text-sm/6 font-semibold text-yellow-500 border border-white rounded-sm p-2">More about me <span aria-hidden="true">→</span></a>
        </div>
      </div>
      <div class="w-1/5 mt-16 h-90 lg:mt-16 flex items-center justify-center">
        <img class="rounded-full w-60 ms:flex sm:w-full" :src="Profil"  alt="my photo">
      </div>
    </div>
  </div>
  
</template>

<style scoped>

</style>
<script setup>
import Profil from '../assets/img/jinwoo.jpg'
</script>
