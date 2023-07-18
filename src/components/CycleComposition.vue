<template>
    <h1>Hola mundo Composition</h1>
</template>

<script lang="ts" setup>
import { onMounted, onUpdated } from 'vue'

onMounted(() => {
    console.log("mounted")
})

onUpdated(() => {
    console.log("updated")
})
</script>

<style scoped>
</style>