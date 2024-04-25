<template>
    <Navbar />
    <h1>Home</h1>
</template>

<script setup>
import Navbar from '@/components/Navbar.vue';
import { defineComponent } from 'vue';

defineComponent({
    name: 'homeView',
    components: {
        Navbar,
    },
});
</script>
