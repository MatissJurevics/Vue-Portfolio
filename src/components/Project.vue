<script setup>
const props = defineProps({
  ImgURL: String,
  GithubURL: String,
  DemoURL: String,
  Title: String,
  Tags: [],
  Description: String,
  Link: String,
});

</script>

<template>

  <div
    class="overflow-hidden aspect-video min-w-[370px] bg-white/30 cursor-pointer rounded-xl relative group"
  >
    <div
      class="rounded-xl z-50 opacity-0 group-hover:opacity-100 transition duration-300 ease-in-out cursor-pointer absolute from-black/80 to-transparent bg-gradient-to-t inset-x-0 -bottom-2 pt-30 text-white flex items-end"
    >
      <div>
        <div
          class="p-4 space-y-3 text-xl group-hover:opacity-100 group-hover:translate-y-0 translate-y-4 pb-10 transform transition duration-300 ease-in-out"
        >
          <div class="font-bold">{{props.Title}}</div>

          <div class="opacity-60 text-sm flex flex-row items-center">
            <p>{{props.Description}}</p>
            <a :href="GithubURL" class="">Github</a>
          </div>
        </div>
      </div>
    </div>
    <a :href="props.DemoURL">
    <img
      alt=""
      class="object-cover w-full aspect-video group-hover:scale-110 transition duration-300 ease-in-out"
      :src="props.ImgURL"
    />
    </a>

  </div>


</template>
