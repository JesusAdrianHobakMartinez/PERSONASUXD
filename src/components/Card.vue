<template>
    <div class="bg-white shadow-md rounded-lg p-4">
      <!-- Contenido de la tarjeta -->
      <slot></slot>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Card',
  };
  </script>
  
  <style scoped>
  /* Estilos específicos para el componente Card */
  </style>