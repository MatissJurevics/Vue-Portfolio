<script setup>

</script>

<template>

  <nav
    class="fixed z-20 flex flex-col md:flex-row items-center bg-black/50 md:bg-transparent  md:justify-between md:px-4 w-screen overflow-hidden h-30 md:h-16"
  >
    <ul class="flex flex-row text-white/60 text-lg">
      <li>
        <a
          href="#main"
          class="md:ml-16 mr-3 py-1 hover:text-white/90 hover:border-white/70  border-white/0 transition duration-200"
        >
          Main
        </a>
      </li>
      <li>
        <a
          href="#about"
          class="mx-3 py-1 hover:text-white/90 hover:border-white/70  border-white/0 transition duration-200"
        >
          About
        </a>
      </li>
      <li>
        <a
          href="#work"
          class="mx-3 py-1 hover:text-white/90 hover:border-white/70  border-white/0 transition duration-200"
        >
          Work
        </a>
      </li>
      <li>
        <a
          href="#contact"
          class="mx-3 py-1 hover:text-white/90 hover:border-white/70  border-white/0 transition duration-200"
        >
          Contact
        </a>
      </li>
      <li>
        <a
          href="../assets/Resume.pdf"
          class="mx-3 py-1 hover:text-white/90 hover:border-white/70  border-white/0 transition duration-200"
        >
          CV/Resume
        </a>
      </li>
    </ul>
    <ul class="flex flex-row items-center text-white/60 text-lg">
      <li>
        <a href="https://github.com/matissjurevics">
          <span
            class="iconify mx-3 opacity-60 hover:opacity-90 transition duration-200"
            data-icon="akar-icons:github-fill"
            data-width="30"
            data-height="30"
          ></span>
        </a>
      </li>
      <li>
        <a href="https://dribbble.com/Saetom" class="mx-3">
          <span
            class="iconify mx-3 opacity-60 hover:opacity-90 transition duration-200"
            data-icon="akar-icons:dribbble-fill"
            data-width="30"
            data-height="30"
          ></span>
        </a>
      </li>
      <li>
        <a href="https://www.linkedin.com/in/matiss-jurevics-121162240/" class="mx-3">
          <span
            class="iconify mx-3 opacity-60 hover:opacity-90 transition duration-200"
            data-icon="akar-icons:linkedin-box-fill"
            data-width="30"
            data-height="30"
          ></span>
        </a>
      </li>
      <li>
        <a
          href="https://blog.saetom.xyz"
          class="md:mr-16 ml-3 opacity-60 hover:opacity-90 transition duration-200"
          >Blog</a
        >
      </li>
    </ul>
  </nav>
</template>
