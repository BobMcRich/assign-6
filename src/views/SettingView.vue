<script setup>
    import { createRouter, createWebHistory } from 'vue-router';
    import SettingsView from '../views/SettingsView.vue';

    const routes = [
    {
        path: '/settings',
        name: 'Settings',
        component: SettingsView,
    },
    // other routes...
    ];

    const router = createRouter({
    history: createWebHistory(import.meta.env.BASE_URL),
    routes,
    });

    export default router;

</script>

<template>


</template>

<style scoped>

</style>