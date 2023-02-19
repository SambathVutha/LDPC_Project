<template>
    <!----<div class=" min-h-full top-0 bg-slate-400 block ">
        !-- Logo --
        <img class=" w-24 h-24 ml-48 inline-block" src="~/assets/img/LDPC_logo1.png">
    !-- Navbar Start --
    <nav class="container mx-auto p-4 inline-block justify-between">
        <ul class=" flex gap-7">
            <li><nuxt-link to="/">Home</nuxt-link></li>
            <li><nuxt-link to="/Test">Test</nuxt-link></li>
            <li><nuxt-link to="/products">Products</nuxt-link></li>
            <li><nuxt-link to="/about">About</nuxt-link></li>
            <li><nuxt-link to="/login">Login</nuxt-link></li>
            <li><nuxt-link to="/register">Register</nuxt-link></li>
        </ul>
    </nav>-->

    <div class=" fixed top-0 w-full bg-slate-300 my-0 lg:justify-between">
        <div class=" inline-block">
            <img class=" w-24 h-24 ml-40 inline-block" src="~/assets/img/LDPC_logo1.png">
        </div>
        <nav class="inline-flex mx-auto p-4 justify-between ml-80">         
            <ul class=" flex gap-7 font-bold">
                <li><nuxt-link to="/">Home</nuxt-link></li>
                <li><nuxt-link to="/Test">Test</nuxt-link></li>
                <li><nuxt-link to="/products">Products</nuxt-link></li>
                <li><nuxt-link to="/about">About</nuxt-link></li>
                <li><nuxt-link to="/login">Login</nuxt-link></li>
                <li><nuxt-link to="/register">Register</nuxt-link></li>
            </ul>
        </nav>
        <div class="inline-block -space-x-2 ml-80">
            <img class="inline-block h-10 w-10 rounded-full ring-2 ring-white" src="~/assets/img/user.jpg" alt="" />
        </div>  
    
    <!-- Navbar End -->
    <!-- Header Start -->
  
    <!-- Header End -->
    </div>
</template>

<script setup>

</script>

<style scoped>

</style>