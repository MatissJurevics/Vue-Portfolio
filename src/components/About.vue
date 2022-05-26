<script setup></script>

<template>
  <section
  id="about"
    class="h-screen w-screen p-20 snap-center bg-[#000b2e] relative flex flex-col justify-center items-center sm:items-start overflow-hidden"
  >

    <h1 class="text-5xl z-10 lg:text-7xl font-bold text-white">About Me <span class="text-white/50">//</span></h1>
    <p
      class="font-mono z-10  mt-4 text-white/70 w-[300px] lg:w-[600px] text-center sm:text-left"
    >
      I am a UI Designer and programmer with experience working with Figma,
      Vuejs, Svelte, Tailwindcss, Firebase and Solidity. In addition to this I
      have a solid understanding of web app security which I leverage
      to develop secure apps.
    </p>
    <a
      href="#work"
      class="mt-8 p-2 z-10 w-32 flex flex-row justify-center bg-transparent border-2 border-pink-500 rounded-xl text-pink-500 hover:bg-pink-500 hover:text-white hover:shadow-lg hover:shadow-pink-500/30 transition duration-300"
    >
      See My Work
    </a>
    <li
      class="animate-one animate-in absolute w-[500px] h-[500px] lg:w-[700px] lg:h-[700px] rounded-full -bottom-32 -left-32 bg-cyan-400/50 blur-3xl"
    ></li>
    <li
      class="animate-two animate-in absolute w-[500px] h-[500px] lg:w-[700px] lg:h-[700px] rounded-full -top-32 -right-16 bg-pink-400/50 blur-3xl"
    ></li>
    <div class="absolute w-full h-24 bg-gradient-to-t from-blue-300/0 to-[#000b2e] top-0 left-0" />

    <div class="absolute w-full h-24 bg-gradient-to-b from-blue-300/0 to-[#000b2e] bottom-0 left-0" />

  </section>
</template>
