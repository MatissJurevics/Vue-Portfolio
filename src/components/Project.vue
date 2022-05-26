<script setup>
  // const props = defineProps({
  //   imgURL: "http://example.com",
  //   GithubURL: "http://example.com",
  //   DemoURL: "http://example.com",
  //   Title: "Test Test",
  //   Libraries: ["Firebase", "Tailwindcss", "Vuejs"],
  //   Description: " Lorem ipsum dolor sit amet consectetur adipisicing elit. In doloribus doloremque, a molestias aperiam enim.",
  // })
</script>

<template>
  <div
    class="w-[350px] h-full mt-4 mr-3 rounded-xl text-white bg-white/30 border-2 border-white/40 backdrop-blur-xl overflow-hidden"
  >
    <img src="https://raw.githubusercontent.com/SeatomGuy/Firebase-ChatApp/main/mainchat.png" alt="Cover" class="w-full h-1/2 border-2 border-slate-400"/>
    <h3 class="text-2xl font-bold mx-3">Sample Title</h3>
    <ul class="flex flex-row mx-3">
      <li class="mr-2 ">Lorem</li>
      <li class="mr-2 ">Lorem</li>
    </ul>
    <p class="ml-3 mt-3 mb-1 text-white/70"> 
      Lorem ipsum dolor sit amet consectetur adipisicing elit. In doloribus
      doloremque, a molestias aperiam enim.
    </p>
    
    <ul class="flex flex-col items-center">
      <a href="" class="w-2/3 h-8 text-center bg-gradient-to-br from-gray-700 to-slate-700 mx-3 rounded-lg">Github</a>
      <a href="" class="w-2/3 h-8 text-center bg-gradient-to-br from-cyan-500 to-teal-500 mx-3 rounded-lg mt-2">Demo</a>
    </ul>
  </div>
</template>
