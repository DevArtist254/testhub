<template>
    <div>
        <h1>Welcome to the homepage</h1>
        <img src="/public/im.jpg" alt="travel" width="360">
        <AppAlert>
            This is an auto-imported component
        </AppAlert>
    </div>
</template>

<script setup lang="ts">
useHead({
    title: 'My App',
    meta: [
        { name: 'description', content: 'My amazing site.' }
    ]
})
</script>