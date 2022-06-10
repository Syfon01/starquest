<template>
<div class="container mx-auto md:px-8 2xl:px-32 md:pb-4 top">
  <nav class="flex flex-wrap items-center justify-between pt-6">
  <div class="flex items-center flex-shrink-0 mr-6 text-white">
    <img src="../assets/img/logo.png" alt="" srcset="" class="w-32 h-16">
    <!-- <span class="text-xl font-semibold tracking-tight">Tailwind CSS</span> -->
  </div>
  <div class="block lg:hidden">
    <button class="flex items-center px-3 py-2 text-teal-200 border border-teal-400 rounded hover:text-white hover:border-white">
      <svg class="w-3 h-3 fill-current" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title></svg>
    </button>
  </div>
  <div class="block w-full lg:flex lg:items-center lg:w-auto">
    <div class="ml-auto text-sm lg:flex-grow nav-link">
      <router-link to="/" class="block mt-4 mr-4 lg:inline-block lg:mt-0 hover:text-white">Home</router-link> 
    <router-link to="/launch" class="block mt-4 mr-4 lg:inline-block lg:mt-0 hover:text-white">Launch</router-link>
    <router-link to="/paper" class="block mt-4 mr-4 lg:inline-block lg:mt-0 hover:text-white">White-Paper</router-link>
    <router-link to="/about" class="block mt-4 mr-4 lg:inline-block lg:mt-0 hover:text-white">About</router-link>
    <router-link to="/contact" class="block mt-4 mr-4 lg:inline-block lg:mt-0 hover:text-white">Contact</router-link>
    </div>
  </div>
</nav>
</div>
</template>
<style >
a{
  font-size: 1.2rem;
  margin-right: 1rem;
  padding: 0.5rem 1rem;
}
.nav-link a.router-link-active{
  background: #E92D42;
  border-radius: 1.5rem;
}
.nav-link a:hover{
  background: #E92D42;
  border-radius: 1.5rem;
}
nav{
  z-index: 1100;
  position: relative;
  top: 0;
}

</style>