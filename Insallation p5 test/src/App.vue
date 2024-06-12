<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
   
      <!-- <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav> -->
 
  </header>

 <RouterView />
 <div class="fixed grid end-0 translate-y-[346px] grid-cols-1 grid-rows-4 text-white">
 <nav class="grid grid-cols-1 grid-rows-4 text-right translate-x-[-270px]">
<a class="row-start-1 font-brødbold text-4xl">about</a>
<a class="row-start-2 font-brødbold text-4xl">dancers</a>
<a class="row-start-3 font-brødbold text-4xl">tour dates</a>
<a class="row-start-4 font-brødbold text-4xl">tickets</a>
 </nav>
</div>

</template>
