<script setup lang="ts">
import { progress } from '@/utils/animation/routage';
import { ref } from 'vue';
import { useRouter } from 'vue-router';

const router = useRouter();
const activeClass = ref(
  'text-blue-700',
)
const inactiveClass = ref(
  'text-white',
)
const navigation = [
    { title: 'Accueil', path:"/", name:"home"},
    { title: 'Evenement',path:"/event", name:"event"},
    { title: 'Site',path:"/site", name:"site"},
    { title: 'Apropos',path:"/about", name:"about"},
]
const callComponentWithDelay = (path:string,interval : number = 2000)=>{
    progress.start()
    setTimeout(()=>{
        progress.finish()
        router.push(path);
    },
    interval);
}

</script>
<template>
<div class="pointer-events-none  fixed inset-x-0 z-30 top-0 mt-3 sm:px-6 sm:pb-5 lg:px-8">
  <div class="pointer-events-auto text-center bg-gray-800  flex items-center justify-between gap-x-6  px-6 py-2.5 sm:rounded-xl sm:py-3 sm:pl-4 sm:pr-3.5">
    <div class="text-sm w-full leading-6 text-white">
        <ul class="flex gap-3 text-white font-semibold"  >
            <li v-for="list in navigation" class="pointer-events-auto cursor-pointer hover:text-blue-700 hover:underline hover:underline-offset-4" @click="callComponentWithDelay(list.path)"  :class="[$route.name === list.name ? activeClass : inactiveClass]">{{ list.name }}</li>
        </ul>
      </div>
    <button type="button" class="-m-3 flex-none p-3 focus-visible:outline-offset-[-4px]">
      <span class="sr-only">menu</span>
      
      <svg xmlns="http://www.w3.org/2000/svg" class="size-6 text-white" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5M12 17.25h8.25" />
      </svg>

    </button>
  </div>
</div>
</template>
  
