<template>
    <span>
        <home-hero></home-hero>
        <about></about>
    </span>
</template>

<script>
import HomeHero from '@/components/HomeHero';
import About from '@/components/About';

export default {
    name: 'home',
    components: {
        HomeHero,
        About
    }
};
</script>
