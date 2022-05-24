<script setup>
import Project from "./Project.vue"
</script>

<template>
  <section
    class="h-screen w-screen p-20 snap-center bg-[#000b2e] relative flex flex-col items-center sm:items-start overflow-hidden"
  >
  
    <div class="z-10 w-full">
      <h1 class="text-5xl lg:text-7xl font-bold text-white text-center sm:text-left">My work <span class="text-white/50">//</span></h1>
      <p
        class="font-mono mt-4 text-white/70 w-[300px] lg:w-[800px] text-center sm:text-left"
      >
        Here are a few examples of different kinds of work that I have done over
        the years varying from UI design products to decentralized web
        apps. These projects show my wide area of expertise while
        hopefully showing that I have a strong understanding of the fundamentals.
      </p>
      <div class="w-full h-[550px] mt-12  ">
        <h2 class="text-3xl font-semibold text-white">Search By topic:</h2>
        <ul class="flex flex-row my-2 w-full border-b-2 border-white/30">
          <li class="text-white/70 hover:text-white/90 transition duration-300 text-lg mr-3 cursor-pointer">Web Develoopment</li>
          <li class="text-white/70 hover:text-white/90 transition duration-300 text-lg mx-3 cursor-pointer">UI design</li>
        </ul>
        <ul class="flex flex-row h-[450px] relative">
          <Project />
          <Project />
          <Project />
          <Project />
          <Project />
        
        </ul>
        <div>

        </div>
      </div>
    </div>
    <li
      class="animate-one animate-in absolute w-[500px] h-[500px] lg:w-[700px] lg:h-[700px] rounded-full -top-32 -right-32 bg-fuchsia-400/50 blur-3xl"
    ></li>
    <li
      class="animate-two animate-in absolute w-[500px] h-[500px] lg:w-[700px] lg:h-[700px] rounded-full -top-48 -left-48 bg-teal-400/50 blur-3xl"
    ></li>
    <div class="absolute w-full h-24 bg-gradient-to-t from-blue-300/0 to-[#000b2e] top-0 left-0" />

  </section>
</template>
