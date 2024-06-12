<script setup>
import { gsap } from 'gsap';

import { onMounted } from 'vue';

onMounted(()=>{
let tl = gsap.timeline();
 
tl.from("#about", {duration: 1, ease: "power4.out", x: 900});
tl.to("#abouttext", {duration: 1, y: -900});

tl.play();

})

</script>
<template>
<div class="left-[300px] top-[500px] bottom-[100px]" id="about">
<h2 class="absolute font-bold text-white text-7xl -rotate-90">about</h2>
  <div class="absolute bottom-[100px] w-[700px] h-[800px] left-[250px] top-[-100px]" >
<p class="font-brød text-white text-2xl" id="abouttext">Cullberg presents a meeting between 14 of Cullberg’s own dancers and 10 external dancers from the street dance community, by the choreographer Hooman Sharifi. They influence eachother and their different backgrounds flavour the performance in various ways. The music by Neda Sanai is based on deconstructed Iranian folk songs.<br><br>From the battle the Dancers rise, as individuals and together. They spring from the fight, the resistance, the coexistence. From the will and necessity to make a stand for something that might be taken from you, and the ability to use your own language. Our language is dance.</p>
  </div>
</div>

</template>