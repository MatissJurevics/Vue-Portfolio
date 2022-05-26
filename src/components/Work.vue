<script setup>
import { ref } from "vue";
import Project from "./Project.vue";
const projects = ref([
  {
    Title: "Firebase ChatApp",
    ImgURL:
      "https://raw.githubusercontent.com/SeatomGuy/Firebase-ChatApp/main/mainchat.png",
    GithubURL: "https://github.com/SeatomGuy/Firebase-ChatApp",
    DemoURL: "https://projects.firechat.saetom.xyz/",
    Description:
      "A instant messaging application with authentication that uses firebase as the backed.",
    Tags: ["Vuejs", "Tailwindcss", "Firebase"],
    Type: "webdev",
  },
  {
    Title: "Markdown Editor",
    ImgURL:
      "https://raw.githubusercontent.com/SeatomGuy/Markdown-Editor/main/Screenshot%202022-03-06%20at%2011-59-11%20Svelte%20%2B%20TS%20%2B%20Vite%20App.png",
    GithubURL: "https://raw.githubusercontent.com/SeatomGuy/Markdown-Editor",
    DemoURL: "https://projects.markdowneditor.saetom.xyz/",
    Description:
      "An application that allows you to imput text as markdown and shows a preview of your input",
    Tags: ["Svelte", "Tailwindcss", "MarkedJS"],
    Type: "webdev",
  },
  {
    Title: "Decentralised Task Manager",
    ImgURL:
      "https://raw.githubusercontent.com/SeatomGuy/Solidity-task-manager/main/ethereumtask.png",
    GithubURL: "https://github.com/SeatomGuy/Solidity-task-manager",
    DemoURL: "https://projects.soliditytasks.saetom.xyz/",
    Description:
      "A task manager that uses a solidity smart contract on the ropsten test net",
    Tags: ["Vuejs", "Tailwindcss", "Solidity", "Ethersjs", "Ropsten-Testnet"],
    Type: "webdev",
  },
  {
    Title: "JS Raycasting Engine",
    ImgURL:
      "https://raw.githubusercontent.com/SeatomGuy/JS-Raycaster/main/Screenshot%202022-03-21%20at%2011-43-27%20%F0%9F%9A%80%20Raycaster%20%F0%9F%9A%80.png",
    GithubURL: "https://raw.githubusercontent.com/SeatomGuy/JS-Raycaster",
    DemoURL: "https://projects.raycaster.saetom.xyz/",
    Description:
      "A Javascript application that turns a 2D map into a 3D environment using a raycasting engine that I made from scratch.",
    Tags: ["Vanilla JS", "HTML Canvas"],
    Type: "webdev",
  },
  {
    Title: "Github Search",
    ImgURL:
      "https://raw.githubusercontent.com/SeatomGuy/svelte-github-search/main/details.png",
    GithubURL:
      "https://raw.githubusercontent.com/SeatomGuy/svelte-github-search",
    DemoURL: "https://projects.githubsearch.saetom.xyz/",
    Description:
      "A web app that uses the github API to allow you to look up github accounts and browse repositories, get links for git clone and open the repo in the github IDE",
    Tags: ["Svelte", "Tailwindcss", "Github API"],
    Type: "webdev",
  },
  {
    Title: "Wireframe UI",
    ImgURL: "https://public-files.gumroad.com/yhzgnqp6yiai5621ab7mzdmtxckt",
    Description:
      "A Figma UI Kit that allows you to quickly create wireframes for your designs",
    GithubURL: "https://saetom.gumroad.com/l/WireframeUIKit",
    Type: "uidesign",
  },
]);
</script>

<template>
  <section
    id="work"
    class="min-h-screen w-screen h-fit pb-16 md:px-20 md:py-10 snap-start bg-[#000b2e] relative flex flex-col items-center sm:items-start"
  >
    <div class="z-10">
      <h1 class="text-5xl mx-auto md:mx-0 mt-4 md:mt-0 z-10 lg:text-7xl font-bold text-white">
        My Work <span class="text-white/50">//</span>
      </h1>
      <p
        class="font-mono z-10 mt-4 text-white/70 w-[300px] lg:w-[600px] mb-4 text-center sm:text-left"
      >
        Here are a few examples of different kinds of work that I have done over
        the years varying from UI design products to decentralized web apps.
        These projects show my wide range of skills while showing
        that I have a strong understanding of the fundamentals.
      </p>
    </div>
    <ul class="w-full z-10 px-3 md:px-0 grid grid-cols-1 lg:grid-cols-2 2xl:grid-cols-3 gap-4">
      <Project v-for="project in projects" :key="project.Title" :Title="project.Title" :Description="project.Description" :ImgURL="project.ImgURL" :GithubURL="project.GithubURL" :DemoURL="project.DemoURL"/>
    </ul>
    <li
      class="animate-one animate-in absolute w-[500px] h-[500px] lg:w-[700px] lg:h-[700px] rounded-full top- -left-32 bg-cyan-400/50 blur-3xl"
    ></li>
    <li
      class="animate-two animate-in absolute w-[500px] h-[500px] lg:w-[700px] lg:h-[700px] rounded-full top-32 -right-16 bg-pink-400/50 blur-3xl"
    ></li>
    <div class="absolute w-full h-24 bg-gradient-to-t from-blue-300/0 to-[#000b2e] top-0 left-0" />

    <div class="absolute w-full h-24 bg-gradient-to-b from-blue-300/0 to-[#000b2e] bottom-0 left-0" />
  </section>
</template>
