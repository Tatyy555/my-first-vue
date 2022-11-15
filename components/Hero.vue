<template>
  <main class="mx-auto lg:max-w-6xl px-5 lg:px-0 pt-14 lg:pt-12">
    <h1
      class="capitalize font-semibold text-[38px] lg:text-7xl text-center leading-snug"
    >
      Welcome to the new<br /><span
        class="font-extrabold bg-clip-text text-transparent bg-gradient-to-r from-violet-600 via-pink-600 to-amber-600"
        >Frontend Development</span
      >
    </h1>
    <p class="mt-10 text-2xl lg:text-3xl text-center font-medium">
      This is my first time for using Vue.js, Nuxt.js and Tailwind CSS together.
    </p>
    <div class="mt-10 lg:mt-14 flex items-center justify-center space-x-4">
      <NuxtLink
        to="#"
        class="px-6 py-3 text-xl bg-violet-700 text-white rounded-full hover:bg-violet-900 transition-all duration-300"
        >Download App</NuxtLink
      >
      <NuxtLink
        class="group text-xl overflow-hidden relative bg-gray-50 ring-1 hover:ring-transparent ring-gray-100 rounded-full transition-all duration-500"
        to="#"
      >
        <div
          class="absolute h-full w-0 group-hover:w-full transition-all duration-500 bg-violet-700"
        ></div>
        <span
          class="block px-6 py-3 transition-all duration-500 group-hover:text-white relative"
          >Take Tour</span
        >
      </NuxtLink>
    </div>
  </main>
</template>
