<script setup>
import Main from "./components/Main.vue"
import About from "./components/About.vue"
import Work from "./components/Work.vue"
import Contact from "./components/Contact.vue"



</script>

<template>

<main class="h-screen overflow-y-scroll overflow-x-hidden snap-y snap-mandatory">
  <Main />
  <About />
  <Work />
  <Contact />


</main>


</template>

<style>
 /* width */
::-webkit-scrollbar {
  width: 8px;
  background:  #000b2e
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