<script setup lang="ts">
import Footer from '@/components/Footer.vue';
import Header from '@/components/Header.vue';
</script>
<template>
<div class=" bg-gray-200 font-roboto">
    <!-- <Header/> -->
    <main class="overflow-x-hidden overflow-y-auto">
        <div class="">
          <slot />
        </div>
      </main>
    <Footer/>
</div>
</template>