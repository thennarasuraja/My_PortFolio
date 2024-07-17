<template>
  <div class="flex w-full h-screen">
    <div class="mt-[100px] w-full">
      <div class="flex justify-center">
        <div class="flex flex-col gap-5">
          <div class="text-[35px] flex justify-center">Services</div>
          <div class="w-full px-[200px] text-[16px] text-gray-600 text-center">
            Far far away, behind the word mountains, far from the countries
            Vokalia and Consonantia
          </div>
        </div>
      </div>
      <div
        class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-5 w-full mt-[20px]"
      >
        <div
          class="bg-gray-500 h-[280px] flex justify-center pt-16 rounded-[6px] hover:bg-[#ffbd39] hover:text-black"
        >
          <div class="flex flex-col gap-3 items-center">
            <img src="/images/web-development.png" class="w-[90px] h-[70px]" />

            <div class="border-[#ffbd39] border-b-2 pb-5">Web Designing</div>
          </div>
        </div>
        <div
          class="bg-gray-500 h-[280px] flex justify-center pt-16 rounded-[6px] hover:bg-[#ffbd39] hover:text-black"
        >
          <div class="flex flex-col gap-3 items-center">
            <img src="/images/coding.png" class="w-[90px] h-[70px]" />

            <div class="border-[#ffbd39] border-b-2 pb-5">Web Developer</div>
          </div>
        </div>
        <div
          class="bg-gray-500 h-[280px] flex justify-center pt-16 rounded-[6px] hover:bg-[#ffbd39] hover:text-black"
        >
          <div class="flex flex-col gap-3 items-center">
            <img src="/images/backend.png" class="w-[90px] h-[70px]" />

            <div class="border-[#ffbd39] border-b-2 pb-5">
              backend Developer
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
