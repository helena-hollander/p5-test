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
 <div class="fixed grid end-0 translate-y-[50vh] grid-cols-1 grid-rows-4 text-white">
 <nav class="grid grid-cols-1 grid-rows-4 uppercase text-right translate-x-[-6vw] text-2xl hover:lowercase">
<a class="row-start-1">about</a>
<a class="row-start-2">dancers</a>
<a class="row-start-3">tour dates</a>
<a class="row-start-4">tickets</a>
 </nav>
</div>

</template>
