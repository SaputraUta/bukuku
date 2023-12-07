<script setup lang="ts">
import { RouterView } from "vue-router";
import { ref } from "vue";
const showSideBar = ref(false);
</script>

<template>
  <div class="flex min-h-screen">
    <div v-if="showSideBar" class="w-64 bg-gray-200 border-r border-gray-200">
      <div class="mt-16">
        <router-link
          to="/"
          class="flex gap-2 mb-8 hover:cursor-pointer hover:scale-105"
          ><img src="./assets/house-solid.svg" alt="" class="ml-5" />
          <p class="text-slate-800text-lg">Home</p></router-link
        >
        <router-link
          to="/about-us"
          class="flex gap-2 mb-8 hover:cursor-pointer hover:scale-105"
          ><img src="./assets/phone-solid.svg" alt="" class="ml-5" />
          <p class="text-slate-800 text-lg">About us</p></router-link
        >
        <router-link to="/contact-us" class="flex gap-2 mb-8 hover:cursor-pointer hover:scale-105"
          ><img src="./assets/address-book-solid.svg" alt="" class="ml-5" />
          <p class="text-slate-800 text-lg">Contact us</p></router-link
        >
      </div>
    </div>
    <div class="flex-1">
      <div
        class="flex justify-between border-b-2 border-gray-200 h-20 items-center relative"
      >
        <button @click="showSideBar = !showSideBar">
          <img src="./assets/bars-solid.svg" alt="" class="ml-5 w-8" />
        </button>
        <div class="flex hover:cursor-pointer items-center mx-auto">
          <img src="./assets/book-solid.svg" alt="book" class="w-10 ml-5" />
          <h2 class="font-bold text-4xl ml-2 text-slate-800">Bukuku</h2>
        </div>
        <div class="mr-16 flex gap-4 items-center">
          <h2 class="text-2xl font-bold text-slate-800">Hi, Saputra!</h2>
          <img
            src="./assets/IMG_9359.jpg"
            alt=""
            class="object-cover w-14 h-14 rounded-full border-2 border-slate-800 hover:cursor-pointer"
          />
        </div>
      </div>
      <div class="ml-5 mt-5 mr-5">
        <router-view />
      </div>
    </div>
  </div>
</template>
