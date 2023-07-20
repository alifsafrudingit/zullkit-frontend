<script setup>
import { RouterView } from 'vue-router'
import Navbar from './components/layouts/Navbar.vue'
import Footer from './components/layouts/Footer.vue'
// import { NavigationBar } from '@/assets/components/NavigationBar'
</script>

<template>
    <Navbar />
    <RouterView />
    <Footer />
</template>

<style scoped>
@import '@/assets/css/styles.css';
</style>
