<template>
	<nav class="mx-auto p-4 bg-blue-50 ">
  <div class="container mx-auto flex items-center justify-between">
    <a href="#" class="ml-5">
      <h1 class="text-3xl font-medium text-blue-700">pathway</h1>
    </a>
    <button id="menu-button" class="lg:hidden" @click="toggleMenu">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" viewBox="0 0 448 512"><path d="M0 96C0 78.3 14.3 64 32 64H416c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32H416c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32H416c17.7 0 32 14.3 32 32z"/></svg>
    </button>
     <div id="menu" :class="{'hidden': !menuOpen}" role="menubar" class="flex flex-col gap-2 z-10 absolute bg-white right-0 left-0 top-16 text-center items-start justify-center max-w-full shadow-xl p-4 lg:flex lg:flex-row lg:static lg:justify-center lg:w-full lg:shadow-none xl:ml-36 lg:ml-14 lg:backdrop-blur-none lg:bg-inherit">
   <a role="menuitem" class="py-1 px-6 text-gray-700 font-medium hover:text-gray-400" href="/">Home</a>
   <a role="menuitem" class="py-1 px-6 text-gray-700 font-medium hover:text-gray-400" href="/">Service</a>
   <a role="menuitem" class="py-1 px-6 text-gray-700 font-medium hover:text-gray-400" href="/">Price</a>
   <a role="menuitem" class="py-1 px-6 text-gray-700 font-medium hover:text-gray-400" href="/">Blog</a>
   <a role="menuitem" class="py-1 px-6 text-gray-700 font-medium hover:text-gray-400" href="/">Contact</a>
      <div class="flex flex-col lg:flex-row lg:justify-center lg:ml-auto">
     <a role="menuitem" class="py-2 px-6 text-gray-700 font-medium text-start hover:text-gray-400" href="/">Login</a>
        <button class="py-2.5 px-4 bg-blue-600 rounded-lg text-white w-auto">Create account</button>
      </div>
    </div>
  </div>
</nav>

<section class="bg-blue-50">
  <div class="lg:flex lg:flex-row lg:items-center lg:justify-between lg:space-x-6">
    <div class="lg:order-2 lg:py-5">
      <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" class="p-5 lg:w-3/4 lg:h-max lg:float-end lg:rounded-2xl " alt="credit:unsplash">
    </div>
    <div class="p-5 py-5">
      <h1 class="py-3 text-xl font-bold text-blue-700 text-left lg:text-3xl xl:text-4xl">Monitor your websites 24/7/365</h1>
      <p class="text-gray-600 text-lg">World among the stalks, and grow familiar with the countless indescribable forms flies</p>
       <hr class="my-4 border-t-2 gray-400 w-full">
       <div class="flex items-center text-orange-500 mr-2">
           <i class="fa-solid fa-star"></i>
           <i class="fa-solid fa-star"></i>
           <i class="fa-solid fa-star"></i>
           <i class="fa-solid fa-star"></i>
           <i class="fa-solid fa-star"></i>
       </div>
       <div>
         <p class="py-2 text-lg text-left">"Two driven jocks help fax my big quiz. Quick, Baz, get my woven flax jodhpurs! "Now fax quiz Jack!."</p>
       <div class="py-3 flex gap-3">
         <img src="https://images.unsplash.com/photo-1559718062-361155fad299?q=80&w=1374&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" class="w-16 h-16 rounded-full" alt="credits:unsplash">
         <div class="text-center">
         <h1 class="text-black font-medium">Theo Gilbert</h1>
         <h1 class="text-gray-600 font-medium">CEO - Google</h1>
         </div>
       </div>
       </div>
    </div>
  </div>
</section>
</template>
<script>
export default {
  data() {
    return {
      menuOpen: false,
    };
  },
  methods: {
    toggleMenu() {
      this.menuOpen = !this.menuOpen;
    },
  },
};
</script>