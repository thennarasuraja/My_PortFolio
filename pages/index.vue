<template>
  <div>
    <SideBar />
    <div class="bg-black text-white w-full h-full px-28">
      <div class="grid grid-cols-2 w-full h-screen">
        <div
          class="flex flex-col pl-20 py-[150px] font-extrabold text-[#ffbd39]"
        >
          <div class="text-2xl">Hello!</div>
          <div class="text-[43px]">
            <div class="text-white">I'm</div>
            <div>THENNARASU RAJA</div>
            <div class="text-[35px] py-3 text-white font-normal">
              A Freelance Web Developer
            </div>
            <div class="flex gap-10 text-[18px] mt-5">
              <button
                class="border border-white py-5 px-8 rounded-full bg-[#ffbd39] font-normal text-black"
              >
                Hire Me
              </button>
              <button
                class="border border-white py-5 px-8 rounded-full bg-black font-normal text-white"
              >
                My Works
              </button>
            </div>
          </div>
        </div>
        <div class="flex justify-center items-center pt-11">
          <img src="/images/thennarasu.png"  class="h-[550px] "/></div>
      </div>

      <div id="about">
        <About />
      </div>
      <div id="resume">
        <Resume />
      </div>
      <div id="services">
        <Services />
      </div>
      <div id="skills">
        <Skills />
      </div>
      <div id="projects">
        <Projects />
      </div>
      <div id="contact">
        <Contact />
      </div>
    </div>
  </div>
</template>
