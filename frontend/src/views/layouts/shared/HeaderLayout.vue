<template>
    <div>
        <MenuVue /> <!-- Aqui estamos usando o componente Menu -->
    </div>
</template>

<script>
import MenuVue from '@/components/NavBar.vue'; // Importando o componente Menu

export default {
    // name: 'HomeView',
    components: {
        MenuVue, // Registrando o componente Menu no componente Home
    },
};
</script>