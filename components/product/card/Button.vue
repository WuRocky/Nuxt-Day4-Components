<script lang="ts" setup>
defineProps({
    buttonText: String,
})
</script>

<template>
    <!-- <button>了解更多</button> -->
    <button href="#" class="btn btn-primary">{{ buttonText }}</button>
</template>

<style scoped></style>
