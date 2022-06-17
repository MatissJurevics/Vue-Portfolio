<template>
  <nav class="navbar fixed z-20 px-10 md:px-20 ">
    <div class="navbar-start list-none text-xl text-white/50 hidden md:flex">
      <li class="mr-3 hover:text-white/90 transition duration-300">
        <a href="#main">Home</a>
      </li>
      <li class="mr-3 hover:text-white/90 transition duration-300">
        <a href="#about">About Me</a>
      </li>
      <li class="mr-3 hover:text-white/90 transition duration-300">
        <a href="#work">Projects</a>
      </li>
      <li class="mr-3 hover:text-white/90 transition duration-300">
        <a href="#contact">Contact</a>
      </li>
    </div>
    <div class="navbar-start md:hidden"></div>
    <div class="navbar-center"></div>

    <div class="navbar-end hidden md:flex md:flex-row list-none opacity-100">
      <li>
        <a href="https://github.com/matissjurevics">
          <span
            class="iconify mx-3 opacity-50 hover:opacity-90 transition duration-200"
            data-icon="akar-icons:github-fill"
            data-width="30"
            data-height="30"
          ></span>
        </a>
      </li>
      <li>
        <a href="https://dribbble.com/Saetom" class="mx-3">
          <span
            class="iconify mx-3 opacity-50 hover:opacity-90 transition duration-200"
            data-icon="akar-icons:dribbble-fill"
            data-width="30"
            data-height="30"
          ></span>
        </a>
      </li>
      <li>
        <a
          href="https://www.linkedin.com/in/matiss-jurevics-121162240/"
          class="mx-3"
        >
          <span
            class="iconify mx-3 opacity-50 hover:opacity-90 transition duration-200"
            data-icon="akar-icons:linkedin-box-fill"
            data-width="30"
            data-height="30"
          ></span>
        </a>
      </li>
      <li>
        <a
          href="https://blog.saetom.xyz"
          class="md:mr-16 ml-3 opacity-50 hover:opacity-90 transition duration-200"
          >Blog</a
        >
      </li>
    </div>
    <div class="navbar-end md:hidden">
        <label for="my-drawer-3">
      <span
        class="iconify cursor-pointer"
        data-icon="ci:hamburger"
        style="color: white"
        data-width="40"
        data-height="40"
      ></span>
        </label>

    </div>
  </nav>
</template>
