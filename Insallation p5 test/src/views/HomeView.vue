<script setup>
import CanvasComp from '@/components/CanvasComp.vue'; //Bagerste canvas comp
import FrontCanvasComp from '@/components/FrontCanvasComp.vue'; //Forreste canvas comp
import HeroComp from '@/components/HeroComp.vue'; //Grafikken på Hero page
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

<style scoped>
#defaultCanvas0 {
  filter: blur(30px);
  -webkit-filter: blur(30px); /*den skal også være den samme som blur, så det virker i browseren*/
 mix-blend-mode: hue; /*Typo forsvinder, hvis ikke blend er hue... ved ikke hvorfor*/
 position: fixed; /*så den ikke flytter sig.*/
}
#defaultCanvas1 {
 opacity: 0.25; /*Opacity 25%*/
 pointer-events: none; /*Så jeg kan klikke på ting bagved*/
 position: fixed;
}

/*defaultCanvas0 og 1 er i style, fordi p5 laver sit eget id, og kan derfor ikke styles med tailwind*/

</style>