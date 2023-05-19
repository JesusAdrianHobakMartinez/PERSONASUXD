<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <header class="">
    <div class="text-center rounded-full  px-8 py-9">
      <span class="text-x4 box-decoration-clone bg-gradient-to-r from-indigo-600 to-pink-500 text-white px-9 ...">
  Formulario de personalidad<br />
  UX
</span>
  </div><br>
  <div class=" bg-white px-4 py-4 ">
  
    <div class="wrapper">
      <HelloWorld msg="Formulario de personas UX" />

      
      <nav class="grid grid-cols-3 divide-x text-center">
      
        <RouterLink class="text-xl  bg-green-400 hover:bg-green-500 hover:text-2xl" to="/"> <strong>INICIO</strong> </RouterLink>
        <RouterLink class=" text-xl   bg-blue-400 hover:bg-blue-500 hover:text-2xl"  to="/personaUX"> <strong>Formulario </strong> </RouterLink>
        <RouterLink class=" text-xl   bg-red-400 hover:bg-red-500  hover:text-2xl"  to="/about"> <strong> Acerca de </strong> </RouterLink>

      </nav>

      
    </div>


  <RouterView />
  </div>
  
  </header>

</template>

