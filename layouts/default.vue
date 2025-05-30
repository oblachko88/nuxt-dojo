<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="container mx-auto p-4 justiy-between">
                <NuxtLink to="/" class="font-bold ">NuxtDojo</NuxtLink>
                <ul class="flex gap-4">
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/about">About</NuxtLink></li>
                    <li><NuxtLink to="/products" class="btn">Products</NuxtLink></li>
                </ul>
            </nav>
        </header>

        <!-- output the page content -->
    
    
        <div class="container mx-auto p-4">
            <slot />
        </div>
    </div>
</template>

<style scooped>
    .router-link-exact-active {
        color: #12b488;
    }
</style>