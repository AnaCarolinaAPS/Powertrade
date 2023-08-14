<!-- Exemplo em Portada.vue -->
<template>
    <div>
      <!-- <h1>Bem-vindo à Portada do Site!</h1> -->
      <!-- Conteúdo da página inicial -->
      <headerLayout></headerLayout>
      <router-view></router-view>
      <footerLayout></footerLayout>
    </div>
  </template>
  
  <script>
  import footerLayout from '@/views/layouts/shared/FooterLayout.vue';
  import headerLayout from '@/views/layouts/shared/HeaderLayout.vue';
  
  export default {
    components: {
        footerLayout,
        headerLayout,
    },
    // Outras configurações do componente
  };
  </script>