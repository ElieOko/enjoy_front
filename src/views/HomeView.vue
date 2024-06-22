<script setup lang="ts">
import ServiceView from '@/components/home/ServiceView.vue';
import IntroView from '@/components/home/IntroView.vue';
//@ts-ignore
import BannerView from '@/components/home/BannerView.vue';
//@ts-ignore
import ShortDesc from '@/components/home/ShortDesc.vue';
//@ts-ignore
import EventSection from '@/components/home/EventSection.vue';



</script>

<template>
  <!--banner-->
  <BannerView/>
  <!--intro-->
  <IntroView/>
  <!--Short description-->
  <ShortDesc/>
  <!--service-->
  <ServiceView/>
  <!--section-event 3-->
  <EventSection/>
  <!--section-avis-->

  <!--section-contact-->
</template>
