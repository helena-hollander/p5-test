<script setup>
import CanvasComp from '@/components/CanvasComp.vue';
import HeroComp from '@/components/HeroComp.vue';
</script>

<template>

  <div class="fixed grid ">
    <CanvasComp></CanvasComp>
  </div>
<HeroComp class="absolute"></HeroComp>

</template>

<style>
#defaultCanvas0 {
  background-color: rgb(236 72 153);
  filter: blur(30px);
  -webkit-filter: blur(30px);
 mix-blend-mode: hue;
 
}

</style>