<script setup>
import "animate.css"
</script>

<template>
  <section
    class="h-screen w-screen justify-center md:justify-start md:px-20 snap-center bg-[#000b2e] relative flex items-center overflow-hidden"
  >
    <div class="animate-in z-10">
      <h1 class="text-5xl lg:text-8xl font-bold text-white ">Matiss</h1>
      <h1 class="text-5xl lg:text-8xl font-bold text-white">
        Jurevics <span class="text-white/50">//</span>
      </h1>
      <p class="font-mono mt-4 mb-8 text-white/70 w-[300px] lg:w-[500px]">
        I am a UI/UX designer / Web Developer / Entrepreneur trying to make awesome
        things on the web<span class="blink">|</span>
      </p>
      <a
        href="#about"
        class="mt-8 p-2 w-32 bg-transparent border-2 border-pink-500 rounded-xl text-pink-500 hover:bg-pink-500 hover:text-white hover:shadow-lg hover:shadow-pink-500/30 transition duration-300"
      >
        Learn More
      </a>
    </div>

    <li
      class="animate-one animate-in absolute w-[500px] h-[500px] lg:w-[700px] lg:h-[700px] rounded-full -top-32 -right-32 bg-cyan-400/50 blur-3xl"
    ></li>
    <li
      class="animate-two animate-in absolute w-[500px] h-[500px] lg:w-[700px] lg:h-[700px] rounded-full -bottom-32 -right-16 bg-pink-400/50 blur-3xl"
    ></li>
    <div class="absolute w-full h-24 bg-gradient-to-b from-blue-300/0 to-[#000b2e] bottom-0 left-0" />
  </section>
</template>

<style>
    .animate-in {
        animation: fadeIn;
        animation-duration: 2s;
    }
    .animate-one {
        animation: sparkle 12s ease-in-out infinite;
    }
    .animate-two {
        animation-delay: 4s;
        animation: sparkle 12s ease-in-out infinite;
    }
    .blink {
        animation: blinck 1.3s steps(2) infinite;
    }
    @keyframes blinck { /*intentionally misspelt*/ 
        from {
            opacity: 0;
        }
        to {
            opacity: 1;
        }
    }
    @keyframes sparkle {
        0% {
            opacity: 0.5;
        }
        50% {
            opacity: 0.7;
        }
        100% {
            opacity: 0.5;
        }
    }

</style>