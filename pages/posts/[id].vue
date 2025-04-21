<template>
    <p>
        Details post {{ id }}
    </p>
</template>

<script setup lang="ts">

useSeoMeta({
    title: 'My amazing site',
    ogTitle: 'My amazing site',
    description: 'This amazing site, let me tell you all about it.',
    ogDescription: 'This amazing site, let me tell you all about it.',
    ogImage: 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.dole.com%2Fen-ca%2Fproduce%2Fpineapple&psig=AOvVaw29ZMlRLoDXhAPEVjNx1g9Z&ust=1745307342406000&source=images&cd=vfe&opi=89978449&ved=0CBAQjRxqFwoTCICSotPO6IwDFQAAAAAdAAAAABAE',
})

const route = useRoute()
const id = ref(route.params.id)

</script>