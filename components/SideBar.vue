<template>
  <div class="text-white">
    <div
      class="w-full h-[80px] flex justify-between py-8 fixed px-28 shadow-md bg-black"
    >
      <div class="text-xl font-bold">THENNARASU</div>
      <div class="grid grid-cols-7 gap-10 text-center font-bold text-[17px]">
        <div class="hover:border-b-2 border-yellow-400 cursor-pointer">
          <nuxt-link to="/">Home</nuxt-link>
        </div>
        <div class="hover:border-b-2 border-yellow-400 cursor-pointer">
          <!-- :class="{
            'border-b-2 border-yellow-400':
              $router.currentRoute.hash == '#about',
          }" -->
          <!-- <a href="#About">About</a>  -->
          <NuxtLink :to="{ path: '/', hash: '#about' }">About</NuxtLink>
        </div>
        <div class="hover:border-b-2 border-yellow-400 cursor-pointer">
          <NuxtLink :to="{ path: '/', hash: '#resume' }">Resume</NuxtLink>
        </div>
        <div class="hover:border-b-2 border-yellow-400 cursor-pointer">
          <NuxtLink :to="{ path: '/', hash: '#services' }">Services</NuxtLink>
        </div>
        <div class="hover:border-b-2 border-yellow-400 cursor-pointer">
          <NuxtLink :to="{ path: '/', hash: '#skills' }">Skills</NuxtLink>
        </div>
        <div class="hover:border-b-2 border-yellow-400 cursor-pointer">
          <NuxtLink :to="{ path: '/', hash: '#projects' }">project</NuxtLink>
        </div>
        <div class="hover:border-b-2 border-yellow-400 cursor-pointer">
          <NuxtLink :to="{ path: '/', hash: '#contact' }">Contact</NuxtLink>
        </div>
      </div>
    </div>
  </div>
</template>
<script setup>
import { watch, ref } from "vue";
import { useRoute } from "vue-router";

const route = useRoute();
const isAboutSectionVisible = ref(false);

// Watch for changes in the route hash
watch(
  () => route.hash,
  (newHash) => {
    isAboutSectionVisible.value = newHash === "#about";
  },
  { immediate: true }
);
</script>
<script>
export default {};
</script>
