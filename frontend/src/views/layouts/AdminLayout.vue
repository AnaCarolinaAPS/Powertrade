<!-- Exemplo em Portada.vue -->
<template>
    <div>
      <h1>Bem-vindo à Portada do Site!</h1>
      <!-- Conteúdo da página inicial -->
      <router-view></router-view>
      <footerLayout></footerLayout>
    </div>
  </template>
  
  <script>
  import footerLayout from '@/views/layouts/shared/FooterLayout.vue';
  
  export default {
    components: {
        footerLayout,
    },
    // Outras configurações do componente
  };
  </script>