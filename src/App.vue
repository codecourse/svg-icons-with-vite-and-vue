<script setup>
import Svg from './components/Svg.vue'
import Bolt from './assets/svg/bolt.svg'
</script>

<template>
    <!-- You can do this, but loads of imported components become cumbersome -->
    <Bolt class="icon" />

    <!-- This is better, one import with ability to pass the name of the svg -->
    <Svg name="bolt" class="icon" />
</template>

<style>
    .icon {
        width: 50px;
        height: 50px;
    }
</style>
