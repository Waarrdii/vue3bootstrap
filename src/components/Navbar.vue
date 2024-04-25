<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Navbar</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown"
                aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavDropdown">
                <ul class="navbar-nav">
                    <fileMenu />
                    <editMenu />
                </ul>
            </div>
        </div>
    </nav>
</template>

<script setup>
import { defineComponent } from 'vue';
import fileMenu from './sub-components/fileMenu.vue';
import editMenu from './sub-components/editMenu.vue'

defineComponent({
    name: 'Navbar',
    components: {
        fileMenu, editMenu,
    },
});
</script>

<style lang="scss" scoped></style>