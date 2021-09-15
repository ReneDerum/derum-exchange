<template>
  <div class="flex-col items-center">
    <h1 class="text-gray-700 text-6xl text-center">Error</h1>
    <p class="text-gray-600 text-xl text-center">
      La ruta especificada no exite, volver a home.
      <br />
      Este proyecto es utilizado en el curso de Vue.js Basico de Platzi.
    </p>
    <router-link
      to="/"
      class="text-green-500 text-center hover:underline uppercase"
      >Volver a Home</router-link
    >
  </div>
</template>
