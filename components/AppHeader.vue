<template>
    <nav>
        <p>logo</p>
        <ul>
            <li>
                <NuxtLink to="/">Home</NuxtLink>
            </li>
            <li>
                <NuxtLink to="/about">About</NuxtLink>
            </li>
            <li>
                <NuxtLink :to="{ name: 'posts-id', params: { id: 123 } }">
                    Post
                </NuxtLink>
            </li>
        </ul>
    </nav>
</template>