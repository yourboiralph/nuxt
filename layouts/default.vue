<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="container mx-auto p-4 flex justify-between">
                <NuxtLink to="/" class="font-bold"> FAKE STORE API</NuxtLink>
                <ul class="flex gap-4">
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/products">Products</NuxtLink></li>
                </ul>
            </nav>
        </header>
    </div>
    <div class="container mx-auto p-4">
        <slot />
    </div>
</template>

<style scoped>
    .router-link-exact-active{
        color: #12b488;
    }
    li{
        text-decoration: none;
        list-style: none;
    }
</style>