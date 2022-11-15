<template>
  <div>
    <header
      class="flex items-center justify-between h-20 max-w-6xl mx-auto px-5 lg:px-0"
    >
      <div
        class="border-2 bg-gradient-to-r from-sky-500 to-indigo-500 w-14 h-14 rounded-full"
      ></div>
      <ul class="md:flex items-center space-x-3 hidden">
        <template :key="`navItem-$[i]`" v-for="(n, i) in nav">
          <li>
            <NuxtLink
              class="inline-block px-3 py-2 bg-gray-50 rounded-full text-xl hover:bg-slate-200 transition-all duration-300"
              :to="n.kink"
            >
              {{ n.name }}
            </NuxtLink>
          </li>
        </template>
      </ul>
      <NuxtLink
        to="#"
        class="px-5 py-2 text-xl bg-violet-700 text-white rounded-full hover:bg-violet-900 transition-all duration-300"
        >Download App</NuxtLink
      >
    </header>
  </div>
</template>

<script setup>
const nav = [
  {
    name: "Home",
    link: "/",
  },
  {
    name: "About",
    link: "/#",
  },
  {
    name: "Product",
    link: "/#",
  },
  {
    name: "Contact",
    link: "/#",
  },
];
</script>