<template>
  <nav class="py-3 sm:mx-3 bg-white sticky top-0 border-b border-gray-100">
  <div class="container md:px-12 md:flex md:justify-between md:items-center">
         <div class="flex items-center justify-between" >
           <a href="#" class="flex items-center text-green-600 text-2xl md:mr-3">&#9650<span class="text-gray-900"> fast</span>
            <span class="text-2xl text-gray-900 font-sans font-bold">Delivery</span>
           </a>
           <span class=" block mx-2 text-3xl bg-gray-100 p-2 rounded-lg md:hidden">
             <svg name="menu" @click="toggleMenu" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.7" stroke="currentColor" class="w-6 h-6">
            <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"/>
            </svg>
           </span>
         </div>
         <ul :class="{ 'top-[80px] opacity-100': isMenuOpen, 'opacity-0 top-[-400px]': !isMenuOpen }" class="p-5 z-10 absolute bg-white/80 backdrop-blur w-full left-0 py-4 opacity-0 top-[-400px] transition-all ease-in duration-500 md:p-0 md:flex md:items-center md:space-x-8 md:static md:w-auto md:opacity-100">
         <li class="md:my-0">
           <a href="#home" class="font-medium duration-500 text-gray-700 hover:text-gray-400">Home</a>
         </li>
         <li class="my-6 md:my-0">
           <a href="#" class="font-medium duration-500 text-gray-700 hover:text-gray-400">Service</a>
         </li>
         <li class="my-6 md:my-0">
           <a href="#" class="font-medium duration-500 text-gray-700 hover:text-gray-400">Service</a>
         </li>
         <li class="my-6 md:my-0">
           <a href="#" class="font-medium duration-500 text-gray-700 hover:text-gray-400">Pricing</a>
         </li>
         <li class="my-6 md:my-0">
           <a href="#" class="font-medium duration-500 text-gray-700 hover:text-gray-400">Blog</a>
         </li>
         <li class="my-6 md:my-0">
           <a href="#" class="font-medium duration-500 text-gray-700 hover:text-gray-400">Login</a>
         </li>
         <a href="#"> <button type="button" class="w-full text-white bg-green-800 font-medium rounded-lg px-3.5 py-2.5 text-center hover:bg-green-500 hover:drop-shadow-md transition duration-400 ease-in-out">Get Started</button></a>
         </ul>
  </div>
</nav>
<section id="home" class="py-5">
  <div class="container flex flex-wrap items-center justify-center mx-auto mt-10 md:px-5 md:flex-row">
  <div class="mb-20 lg:mb-0 lg:w-1/2">
    <div class="p-3 flex sm:ml-2">
      <h1 class="px-2 py-1 border-b bg-green-100 rounded-lg text-sm font-bold text-green-900">NEW</h1>
      <p class="ml-2 text-green-900 font-medium">24/7 onside business coaching</p>
    </div>
  <h1 class="max-w-xl text-5xl leading-none text-gray-900 font-extrabold font-sans text-center lg:text-10xl lg:text-left lg:leading-tight mb-5">
  proident, sunt in culpa qui officia deserunt mollit</h1>
  <p class="max-w-xl text-center text-gray-500 lg:text-left lg:max-w-md lg:text-xl">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod qui.</p>
  <div class="flex justify-center mt-14 lg:justify-start">
    <button type="button" class="text-white bg-green-800 font-medium rounded-lg px-5 py-4 text-center hover:bg-green-700 hover:drop-shadow-md transition duration-300 ease-in-out">Learn more</button>
    <button type="button" class="ml-4 text-gray-900 bg-gray-200 font-medium rounded-lg px-5 py-4 text-center hover:bg-gray-300 hover:drop-shadow-md transition duration-300 ease-in-out">Learn more</button>
  </div>
  </div>
  <div class="lg:w-96 sm:w-full sm:px-5">
  <img class="ml-auto rounded-lg" src="https://plus.unsplash.com/premium_photo-1706561439918-424f60089f17?q=80&w=1374&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D">
  </div>
</div>
</section>
</template>
<script>
export default {
  data() {
    return {
      isMenuOpen: false
    };
  },
  methods: {
    toggleMenu() {
      this.isMenuOpen = !this.isMenuOpen;
    }
  }
};
</script>
