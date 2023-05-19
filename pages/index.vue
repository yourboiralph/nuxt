<template>
    <div>
        <h1 class="font-bold text-center">WELCOME TO FAKESTOREAPI</h1>
    </div>
</template>

<script setup>

    //fetch products
    const {data: products } = await useFetch('https://fakestoreapi.com/products/')


</script>

<style scoped>
    li{
        text-decoration: none;
        list-style: none;
    }
</style>
