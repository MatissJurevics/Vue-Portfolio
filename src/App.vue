<script setup>
import Main from "./components/Main.vue"
import About from "./components/About.vue"
import Work from "./components/Work.vue"
import Contact from "./components/Contact.vue"
import Nav from "./components/Nav.vue"


</script>

<template>
<Nav/>
<main class="h-screen overflow-scroll snap-y snap-mandatory">
  <Main />
  <About />
  <Work />
  <Contact />
</main>


</template>