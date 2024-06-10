<script setup>
import CanvasComp from '@/components/CanvasComp.vue';
import FrontCanvasComp from '@/components/FrontCanvasComp.vue';
import HeroComp from '@/components/HeroComp.vue';
</script>

<template>

  <div>
    <CanvasComp></CanvasComp>
  </div>
<HeroComp class="absolute z-10"></HeroComp>
<div>
<FrontCanvasComp></FrontCanvasComp>
</div>
</template>

<style>
#defaultCanvas0 {
  filter: blur(30px);
  -webkit-filter: blur(30px);
 mix-blend-mode: hue;
 position: fixed;
}
#defaultCanvas1 {
 opacity: 0.25;
 pointer-events: none;
 position: fixed;
}

</style>