<script setup>
import Nav from "./components/newNav.vue";
import Main from "./components/Main.vue";
import About from "./components/About.vue";
import Work from "./components/Work.vue";
import Contact from "./components/Contact.vue";
</script>

<template>
  <main class="">
    <div class="drawer drawer-end">
      <input type="checkbox" id="my-drawer-3" class="drawer-toggle" />
      <div
        class="drawer-content h-screen w-screen overflow-y-scroll overflow-x-hidden snap-y snap-mandatory"
      >
        <Nav />
        <Main />
        <About />
        <Work />
        <Contact />
      </div>

      <div class="drawer-side">
        <label for="my-drawer-3" class="drawer-overlay"></label>
        <ul
          class="menu p-4 overflow-y-auto flex flex-col justify-between w-80 bg-black/40"
        >
          <!-- Sidebar content here -->

          <ul>
            <li><a href="#main">Home</a></li>
            <li><a href="#about">About Me</a></li>
            <li><a href="#work">Projects</a></li>
            <li><a href="#contact">Contact Me</a></li>
            <li>
              <a
                href="Resume.pdf"
                >Resume / CV</a
              >
            </li>
          </ul>

          <ul>
            <li>
              <a href="https://github.com/matissjurevics"
                ><span
                  class="iconify mx-3 opacity-50 hover:opacity-90 transition duration-200"
                  data-icon="akar-icons:github-fill"
                  data-width="30"
                  data-height="30"
                ></span
                >Github</a
              >
            </li>
            <li>
              <a href="https://www.linkedin.com/in/matiss-jurevics-121162240/"
                ><span
                  class="iconify mx-3 opacity-50 hover:opacity-90 transition duration-200"
                  data-icon="akar-icons:linkedin-box-fill"
                  data-width="30"
                  data-height="30"
                ></span
                >LinkedIn</a
              >
            </li>
            <li>
              <a href="https://dribbble.com/Saetom"
                ><span
                  class="iconify mx-3 opacity-50 hover:opacity-90 transition duration-200"
                  data-icon="akar-icons:dribbble-fill"
                  data-width="30"
                  data-height="30"
                ></span
                >Dribbble</a
              >
            </li>
            <li>
              <a href="https://blog.saetom.xyz"
                ><span
                  class="iconify mx-3 opacity-50 hover:opacity-90 transition duration-200"
                  data-icon="carbon:blog"
                  style="color: white"
                  data-width="30"
                  data-height="30"
                ></span
                >Blog</a
              >
            </li>
          </ul>
        </ul>
      </div>
    </div>
  </main>
</template>

<style>
/* width */
::-webkit-scrollbar {
  width: 8px;
  background: #000b2e;
}

/* Track */
::-webkit-scrollbar-track {
  box-shadow: inset 0 0 5px grey;
  border-radius: 10px;
}

/* Handle */
::-webkit-scrollbar-thumb {
  background: #555;
}
</style>
