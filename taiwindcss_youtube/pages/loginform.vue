<template>
<div class="flex h-screen">
<img class="hidden lg:block w-1/2 px-3 py-3" src="https://plus.unsplash.com/premium_photo-1664461662767-41fe84f7748d?q=80&w=1374&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="credits:unsplash">
<div class="flex flex-col justify-center items-center w-full lg:w-1/2 font-serif">
  <div>
    <div class="text-xl text-center font-bold lg:text-left"> 
      <span class="text-green-600">&#9650</span>
      <span>Farm man</span> 
    
    </div>
     <div class="text-3xl text-center font-bold lg:text-left mt-3"> 
      <h2>Hello,</h2>
         <h2>Welcome back</h2>
    </div>
    <!-- login form -->
    <form action="" class="mt-8 w-[80%] lg:w-96 mx-auto space-y-4">
      <h4>Login to Manage your account</h4>
      <input
      class="border w-full px-4 py-2"
       type="email" placeholder="Email">
        <input
      class="border w-full px-4 py-2"
       type="password" placeholder="Password">

       <div class="text-blue-600 cursor-pointer hover:text-blue-400">Forget Your Password ?</div>
       <button
       class=" bg-green-600 w-full rounded text-white py-2 hover:bg-green-500"
       >Login</button>
    </form>
  </div>
  <div class="text-center space-y-4 mt-4 font-bold">
    <span>or</span>
    <div class="flex justify-center items-center gap-8">
      <i class="fa-brands fa-instagram text-2xl cursor-pointer"></i>
       <i class="fa-brands fa-facebook text-2xl cursor-pointer"></i>
      <i class="fa-brands fa-linkedin text-2xl cursor-pointer"></i>
    </div>
  </div>
  <div class="mt-4 text-sm text-center">dont have an account ?<span class="text-green-600 cursor-pointer">sign up</span></div>
</div>
</div>
</template>