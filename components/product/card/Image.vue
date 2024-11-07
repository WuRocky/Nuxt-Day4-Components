<script setup lang="ts">
defineProps({
    imageUrl: String,
    altText: String,
})
</script>

<template>
    <img :src="imageUrl" :alt="altText" class="card-img-top">
</template>

<style scoped>
</style>
