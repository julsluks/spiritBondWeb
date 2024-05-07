<template>
  <div class="bg-blue-950">
    <NuxtLayout name="navbar" />
    <NuxtPage />    
    <NuxtLayout name="footer" />
  </div>
</template>

<style>
/* Estilo general de la barra de desplazamiento */
::-webkit-scrollbar {
    width: 10px; /* Ancho de la barra de desplazamiento */
}

/* Estilo de la parte de fondo de la barra de desplazamiento */
::-webkit-scrollbar-track {
    background-color: #b4c8ff; /* Color de fondo */
}

/* Estilo del "pulgar" de la barra de desplazamiento */
::-webkit-scrollbar-thumb {
    background-color: #5161f3; /* Color del pulgar */
    border-radius: 5px; /* Bordes redondeados del pulgar */
}

/* Estilo cuando se pasa el ratón sobre la barra de desplazamiento */
::-webkit-scrollbar-thumb:hover {
    background-color: #1828b9; /* Cambiar el color del pulgar al pasar el ratón */
}

</style>