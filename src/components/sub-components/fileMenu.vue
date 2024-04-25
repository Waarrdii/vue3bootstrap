<template>
    <li class="nav-item dropdown">
        <a class="nav-link" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            File
        </a>
        <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
        </ul>
    </li>
</template>

<script setup>
import { defineComponent } from 'vue';

defineComponent({
    name: 'FileMenu',
})
</script>

<style lang="scss" scoped></style>