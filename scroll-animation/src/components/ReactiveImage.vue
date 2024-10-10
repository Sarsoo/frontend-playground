<script setup lang="ts">

</script>

<template>

<img src="https://placehold.co/600x400?text=Hello+World" class="swell"/>

</template>

<style scoped>

@supports (animation-timeline: view()) {
    @media screen and (prefers-reduced-motion: no-preference) { 

        .swell {
            animation-name: swell;
            animation-fill-mode: forwards;
            animation-timeline: view();
            animation-timing-function: ease-out;
        }

        @keyframes swell {

            50% {
                transform: scale(1.1) rotate(-10deg) skewY(-10deg);
            }

            to {
                transform: scale(1.2) rotate(10deg) skewY(10deg);
                filter: drop-shadow(0 0 2em);
            }
        }
    }
}


</style>
