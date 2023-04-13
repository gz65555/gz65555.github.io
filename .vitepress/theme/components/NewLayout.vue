<template>
    <ClientOnly>
        <Layout />
        <Copyright />
    </ClientOnly>
</template>
<script setup>
import DefaultTheme from 'vitepress/theme'
import Copyright from './Copyright.vue'
const { Layout } = DefaultTheme
</script>
