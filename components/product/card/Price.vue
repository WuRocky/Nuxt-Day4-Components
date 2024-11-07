<script setup lang="ts">
defineProps({
    price: String,
})
</script>

<template>
    <p class="card-text">{{price}}</p>
</template>

<style scoped></style>
