<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <header class="">
    <div class="text-center rounded-full  px-8 py-9">
      <p class="text-8xl ...">ISCLAB ...</p>
      <p class="text-lg ...">Laboratorio de sistemas y aplicaciones web ...</p>
  </div><br>
  <div class=" bg-white px-4 py-4 ">
  
    <div class="wrapper">
      <HelloWorld msg="ISCLAB" />

      
      <nav class="grid grid-cols-1 divide-x text-center">
      
        <RouterLink class=" text-x120"  to="/about"> <strong> ISCLAB </strong> </RouterLink>

      </nav>

      
    </div>


  <RouterView />
  </div>
  
  </header>

</template>

