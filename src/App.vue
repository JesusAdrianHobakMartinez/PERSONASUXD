<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <header class="">
    <div class="text-center rounded-full  px-8 py-9">
      <span class="text-x4 box-decoration-clone bg-gradient-to-r from-blue-600 to-pink-500 text-white px-9 ...">
  Formulario de personalidad<br />
  UX
</span>
  </div><br>
  <div class=" bg-white px-4 py-4 ">
  
    <div class="wrapper">
      <HelloWorld msg="Formulario de personas UX" />

      
      <nav class="grid grid-cols-1 divide-x text-center">
      
        <RouterLink class="text-xl  bg-blue-500 hover:bg-blue-500 hover:text-2x2" to="/"> <strong>INICIO</strong> </RouterLink>
        <RouterLink class=" text-xl   bg-blue-500 hover:bg-blue-500 hover:text-2x2"  to="/personaUX"> <strong>Formulario </strong> </RouterLink>
        <RouterLink class=" text-xl   bg-blue-500 hover:bg-blue-500  hover:text-2x2"  to="/about"> <strong> Acerca de </strong> </RouterLink>

      </nav>

      
    </div>


  <RouterView />
  </div>
  
  </header>

</template>

