<script setup></script>

<template>
  <section
    class="h-screen w-screen p-20 snap-center bg-[#000b2e] relative flex flex-col justify-center items-center sm:items-start overflow-hidden"
  >
    <h1 class="text-5xl lg:text-7xl font-bold text-white">About Me <span class="text-white/50">//</span></h1>
    <p
      class="font-mono mt-4 text-white/70 w-[300px] lg:w-[600px] text-center sm:text-left"
    >
      I am a UI Designer and programmer with experience working with Figma,
      Vuejs, Svelte, Tailwindcss, Firebase and Solidity. In addition to this I
      have a solid understanding of web app security which I leverage
      to develop secure apps.
    </p>
    <button
      class="mt-8 p-2 w-32 bg-transparent border-2 border-pink-500 rounded-xl text-pink-500 hover:bg-pink-500 hover:text-white hover:shadow-lg hover:shadow-pink-500/30 transition duration-300"
    >
      See My Work
    </button>
    <li
      class="animate-one animate-in absolute w-[500px] h-[500px] lg:w-[700px] lg:h-[700px] rounded-full -bottom-32 -right-32 bg-cyan-400/50 blur-3xl"
    ></li>
    <li
      class="animate-two animate-in absolute w-[500px] h-[500px] lg:w-[700px] lg:h-[700px] rounded-full -top-32 -right-16 bg-pink-400/50 blur-3xl"
    ></li>
  </section>
</template>
