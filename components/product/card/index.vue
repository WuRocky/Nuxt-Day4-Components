<script setup lang="ts">
defineProps({
    imageUrl: String,
    altText: String,
    title: String,
    price: String,
    buttonText: String,
})  
</script>

<template>
    <div class="card card-border" style="width: 18rem;">
        <ProductCardImage :imageUrl="imageUrl" :atlText="altText" />
        <div class="card-body text-center">
            <ProductCardTitle :title="title" />
            <ProductCardPrice :price="price" />
            <ProductCardButton :buttonText="buttonText" />
        </div>
    </div>

</template>

<style scoped>
    .card-border{
        width: 18rem;
    }
</style>
