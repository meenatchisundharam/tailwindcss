<template>
  <nav class="p-5 sticky top-0 z-50 bg-black">
    <div class="flex">
        <a href="#" class=" lg:ml-5">
            <h1 class="text-4xl font-extrabold text-white md:text-[32px] xl:text-[42px] md:font-bold xl:font-bold">kalles</h1>
        </a>
        <button id="menu-button" class="lg:hidden mt-2 ml-auto" @click="open = !open">
            <i class="fa-solid fa-bars text-white text-2xl" v-if="!open"></i>
            <i class="fa-solid fa-xmark text-white text-2xl" v-else></i>
        </button>
        <div id="menu"
        :class="{'hidden': !open}"
        role="menubar"
        class="hidden lg:flex lg:flex-row lg:items-center lg:justify-center xl:ml-auto">
            <a
          role="menuitem"
          class="py-3 px-6 text-gray-200 text-[17px] font-medium hover:text-cyan-600"
          href="/"
        >Demos</a>
             <div class="lg:flex lg:flex-col lg:items-center">
          <span class="lg:bg-blue-500 lg:text-xs lg:text-white lg:px-2 lg:rounded-full lg:ml-auto -mt-3">New</span>
  <a href="#" class=" text-gray-200 text-[17px] font-medium -mt-1 hover:text-cyan-600">Special Deal</a>
        </div>
            <a
          role="menuitem"
          class="py-3 px-6 text-gray-200 text-[17px] font-medium hover:text-cyan-600"
          href="/"
        >Features</a>
            <div class="lg:flex lg:flex-col lg:items-center">
          <span class="lg:bg-red-500 lg:text-xs lg:text-white lg:px-3 lg:rounded-full lg:ml-14 -mt-3">Hot</span>
          <a href="#" class="px-6 text-gray-200 text-[17px] font-medium hover:text-cyan-600 -mt-1">Performance</a>
        </div>
            <a
          role="menuitem"
          class="py-3 px-6 text-gray-200 text-[17px] font-medium hover:text-cyan-600"
          href="/"
        >Support</a>
             <a
          role="menuitem"
          class="py-2 px-6 text-gray-200 text-[17px] font-medium hover:text-cyan-600"
          href="/"
        >Open Free Store</a>
 <div class="effect-custom rounded-2xl relative bg-slate-950 xl:ml-28 xl:mr-6">
  <a href="sundhar" class="flex items-center justify-center relative gap-1 py-2  backdrop-blur-3xl border-gray-300 bg-black border-2 text-white font-medium rounded-md hover:bg-gray-800 xl:py-3 xl:px-4">
    <svg class="cta_icon mr-2 z-10 text-white" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20" fill="none">
      <path d="M4.16686 11.6667H15.1133C15.9573 11.6667 16.3793 11.6667 16.7153 11.5093C17.0112 11.3707 17.2599 11.1481 17.4304 10.8693C17.6238 10.5528 17.6705 10.1333 17.7637 9.29448L18.2512 4.90695C18.2796 4.65073 18.2939 4.52262 18.2527 4.42346C18.2165 4.33638 18.1518 4.26414 18.0693 4.21856C17.9753 4.16666 17.8464 4.16666 17.5886 4.16666H3.7502M1.66675 1.66666H2.70711C2.92763 1.66666 3.03789 1.66666 3.12415 1.7086C3.2001 1.74552 3.26303 1.80464 3.30461 1.87813C3.35185 1.96161 3.35873 2.07166 3.37248 2.29175L4.12768 14.3749C4.14144 14.595 4.14831 14.7051 4.19555 14.7885C4.23713 14.862 4.30007 14.9211 4.37601 14.9581C4.46227 15 4.57253 15 4.79305 15H15.8334M6.25008 17.9167H6.25842M13.7501 17.9167H13.7584M6.66675 17.9167C6.66675 18.1468 6.4802 18.3333 6.25008 18.3333C6.01996 18.3333 5.83341 18.1468 5.83341 17.9167C5.83341 17.6865 6.01996 17.5 6.25008 17.5C6.4802 17.5 6.66675 17.6865 6.66675 17.9167ZM14.1667 17.9167C14.1667 18.1468 13.9802 18.3333 13.7501 18.3333C13.52 18.3333 13.3334 18.1468 13.3334 17.9167C13.3334 17.6865 13.52 17.5 13.7501 17.5C13.9802 17.5 14.1667 17.6865 14.1667 17.9167Z" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"></path>
    </svg>
    <span class="cta_text text-white z-10">Buy Now $89</span>
    <div class="absolute inset-0 overflow-hidden flex justify-center items-center">
      <span class="w-full h-full bg-gradient-to-r from-violet-700 to-indigo-700 animate-pulse bg-opacity-40"></span>
      <span class="w-full h-full bg-gradient-to-r from-indigo-700 to-cyan-500 animate-pulse delay-150 bg-opacity-40"></span>
      <span class="w-full h-full bg-gradient-to-r from-cyan-500 to-violet-700 animate-pulse delay-300 bg-opacity-40"></span>
    </div>
  </a>
</div>
  </div>
        <div v-if="open" role="menubar" class="flex flex-col gap-2 z-10 max-h-screen absolute bg-black/80 backdrop-blur bg-opacity-70 overflow-hidden w-80 right-0 top-[75px] text-center place-items-start shadow-xl p-4 lg:hidden">
            <i @click="open = false" class="fa-solid fa-xmark self-end lg:hidden"></i>
          <a href="#" class="">
        <h1 class="text-4xl font-extrabold text-white ml-20">kalles</h1>
      </a>
            <a role="menuitem" class="py-3 px-6 text-white text-[17px] font-medium hover:text-cyan-600" href="/">Demos</a>

            <a href="#" class="px-5 text-gray-200 text-[17px] font-medium -mt-1 hover:text-cyan-600">Special Deal</a>

            <a role="menuitem" class="py-3 px-6 text-gray-200 text-[17px] font-medium hover:text-cyan-600" href="/">Features</a>

            <a href="#" class="px-6 text-gray-200 text-[17px] font-medium hover:text-cyan-600 ">Performance</a>

            <a role="menuitem" class="py-3 px-6 text-white font-medium text-[17px] hover:text-cyan-600" href="/">Support</a>

            <a role="menuitem" class="px-6 text-white font-medium text-[17px] hover:text-cyan-600" href="/">Open Store Free</a>
            <div class="effect-custom rounded-2xl relative bg-slate-950 w-full px-7 ml-4 py-4">
  <a href="sundhar" class="flex items-center justify-center relative gap-1 py-2  backdrop-blur-3xl border-gray-300 bg-black border-2 text-white font-medium rounded-md hover:bg-gray-800 xl:py-3 xl:px-4">
    <svg class="cta_icon mr-2 z-10 text-white" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20" fill="none">
      <path d="M4.16686 11.6667H15.1133C15.9573 11.6667 16.3793 11.6667 16.7153 11.5093C17.0112 11.3707 17.2599 11.1481 17.4304 10.8693C17.6238 10.5528 17.6705 10.1333 17.7637 9.29448L18.2512 4.90695C18.2796 4.65073 18.2939 4.52262 18.2527 4.42346C18.2165 4.33638 18.1518 4.26414 18.0693 4.21856C17.9753 4.16666 17.8464 4.16666 17.5886 4.16666H3.7502M1.66675 1.66666H2.70711C2.92763 1.66666 3.03789 1.66666 3.12415 1.7086C3.2001 1.74552 3.26303 1.80464 3.30461 1.87813C3.35185 1.96161 3.35873 2.07166 3.37248 2.29175L4.12768 14.3749C4.14144 14.595 4.14831 14.7051 4.19555 14.7885C4.23713 14.862 4.30007 14.9211 4.37601 14.9581C4.46227 15 4.57253 15 4.79305 15H15.8334M6.25008 17.9167H6.25842M13.7501 17.9167H13.7584M6.66675 17.9167C6.66675 18.1468 6.4802 18.3333 6.25008 18.3333C6.01996 18.3333 5.83341 18.1468 5.83341 17.9167C5.83341 17.6865 6.01996 17.5 6.25008 17.5C6.4802 17.5 6.66675 17.6865 6.66675 17.9167ZM14.1667 17.9167C14.1667 18.1468 13.9802 18.3333 13.7501 18.3333C13.52 18.3333 13.3334 18.1468 13.3334 17.9167C13.3334 17.6865 13.52 17.5 13.7501 17.5C13.9802 17.5 14.1667 17.6865 14.1667 17.9167Z" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"></path>
    </svg>
    <span class="cta_text text-white z-10">Buy Now $89</span>
    <div class="absolute inset-0 overflow-hidden flex justify-center items-center">
      <span class="w-full h-full bg-gradient-to-r from-violet-700 to-indigo-700 animate-pulse bg-opacity-40"></span>
      <span class="w-full h-full bg-gradient-to-r from-indigo-700 to-cyan-500 animate-pulse delay-150 bg-opacity-40"></span>
      <span class="w-full h-full bg-gradient-to-r from-cyan-500 to-violet-700 animate-pulse delay-300 bg-opacity-40"></span>
    </div>
  </a>
</div>
        </div>
    </div>
</nav>

<section class="p-0 m-0 box-border relative h-screen bg-black">
  <div class="relative bg-gray-900">
    <img loading="lazy" class="h-full w-full object-cover" src="https://images.unsplash.com/photo-1717426793419-2aef630b8435?q=80&w=1385&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" />
    <div class="absolute inset-0 top-24 z-20 xl:top-40">
         <div class="bg-opacity-50 p-4 rounded-md">
        <p class="z-20 bg-custom-gradient bg-clip-text py-4 pb-1 text-center text-xl text-transparent sm:text-3xl md:text-3xl lg:text-3xl xl:text-4xl">
          One-stop Shopify Theme
        </p>
      </div>

      <div class="">
        <h1 class="z-20 text-center text-4xl font-bold text-white sm:py-4 sm:text-4xl md:text-4xl lg:text-7xl xl:py-5 xl:font-semibold">
          Prime Quality <br />
          Premium Design
        </h1>
      </div>
      <p class="z-20 p-5 py-7 text-center text-gray-400 md:pt-0 md:text-lg lg:py-5 xl:px-72 sm:px-36">Craft a beautiful and high-converting Shopify store with Kalles multipurpose theme.Optimized for eCommerce, speed and user experiences.</p>
      <div class="sm:absolute sm:left-[25%] sm:flex sm:flex-row sm:gap-4 md:absolute md:left-[25%] md:flex md:flex-row lg:absolute lg:left-[30%] xl:absolute xl:left-[35%] xl:py-7">
        <div class="flex">
          <div class="effect-custom m-auto rounded-2xl">
            <a href="sundhar" class="relative flex items-center justify-center gap-1 rounded-md border-2 py-2 border-gray-300 bg-black font-medium text-white backdrop-blur-3xl hover:bg-gray-800 sm:py-2 lg:py-3 md:py-3 xl:py-3">
              <i class="fa-solid fa-wand-magic-sparkles h-5 w-5 text-white"></i>
              <span class="cta_text z-10 text-white md:text-xl xl:text-xl">Explore Demos</span>
              <div class="absolute inset-0 flex items-center justify-center overflow-hidden">
                <span class="h-full w-full animate-pulse bg-opacity-40 bg-gradient-to-r from-violet-700 to-indigo-700"></span>
                <span class="h-full w-full animate-pulse bg-opacity-40 bg-gradient-to-r from-indigo-700 to-cyan-500 delay-150"></span>
                <span class="h-full w-full animate-pulse bg-opacity-40 bg-gradient-to-r from-cyan-500 to-violet-700 delay-300"></span>
              </div>
            </a>
          </div>
        </div>
        <div class="group flex items-center justify-center gap-2 py-4 font-bold text-white md:ml-10">
        <i class="fa-brands fa-shopify h-5 w-5 mb-2 text-white md:text-xl xl:text-2xl group-hover:text-cyan-600"></i>
        <span class="sm:text-lg md:text-xl lg:text-xl xl:text-xl group-hover:text-cyan-600">Open store free</span>
    </div>
      </div>
      <div class="relative md:py-16 xl:py-24">
        <p class="p-5 text-center text-gray-400 sm:py-20 sm:px-32 md:text-lg md:py-8 lg:py-14 xl:pt-7 xl:px-96">Get 3 months trial Shopify with 1$/month, exclusive Shopify deal for The4's customers</p>
      </div>
    </div>
    <svg viewBox="0 0 1240 1252" fill="none" xmlns="http://www.w3.org/2000/svg" class="absolute inset-0 z-10 h-full w-full">
      <g class="eff-1 eff" filter="url(#filter0_f_1390_2298)">
        <path d="M885.857 160.25L1024.14 911.075C1026.99 926.564 1042.13 936.591 1057.5 933.177V933.177C1072.87 929.763 1082.34 914.271 1078.37 899.031L885.857 160.25Z" fill="url(#paint0_linear_1390_2298)"></path>
      </g>
      <g class="eff-2 eff" filter="url(#filter1_f_1390_2298)">
        <path d="M353.786 160.25L215.507 911.075C212.655 926.564 197.517 936.591 182.143 933.177V933.177C166.768 929.763 157.298 914.271 161.269 899.031L353.786 160.25Z" fill="url(#paint1_linear_1390_2298)"></path>
      </g>
      <g class="eff-3 eff" filter="url(#filter2_f_1390_2298)">
        <path d="M620 163L648.095 1063.01C648.59 1078.87 635.868 1092 620 1092V1092C604.132 1092 591.41 1078.87 591.905 1063.01L620 163Z" fill="url(#paint2_linear_1390_2298)"></path>
      </g>
      <defs>
        <filter id="filter0_f_1390_2298" x="725.857" y="0.249634" width="513.422" height="1093.6" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
          <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
          <feBlend mode="normal" in="SourceGraphic" in2="BackgroundImageFix" result="shape"></feBlend>
          <feGaussianBlur stdDeviation="80" result="effect1_foregroundBlur_1390_2298"></feGaussianBlur>
        </filter>
        <filter id="filter1_f_1390_2298" x="0.363525" y="0.249634" width="513.422" height="1093.6" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
          <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
          <feBlend mode="normal" in="SourceGraphic" in2="BackgroundImageFix" result="shape"></feBlend>
          <feGaussianBlur stdDeviation="80" result="effect1_foregroundBlur_1390_2298"></feGaussianBlur>
        </filter>
        <filter id="filter2_f_1390_2298" x="431.891" y="3" width="376.218" height="1249" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
          <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
          <feBlend mode="normal" in="SourceGraphic" in2="BackgroundImageFix" result="shape"></feBlend>
          <feGaussianBlur stdDeviation="80" result="effect1_foregroundBlur_1390_2298"></feGaussianBlur>
        </filter>
        <linearGradient id="paint0_linear_1390_2298" x1="857.643" y1="178" x2="1057.5" y2="933.177" gradientUnits="userSpaceOnUse">
          <stop stop-color="rgba(255,255,255,0.5)"></stop>
          <stop offset="1" stop-color="rgba(255,255,255,0.5)" stop-opacity="0.95"></stop>
        </linearGradient>
        <linearGradient id="paint1_linear_1390_2298" x1="382" y1="178" x2="182.143" y2="933.177" gradientUnits="userSpaceOnUse">
          <stop stop-color="rgba(255,255,255,0.5)"></stop>
          <stop offset="1" stop-color="rgba(255,255,255,0.5)" stop-opacity="0.95"></stop>
        </linearGradient>
        <linearGradient id="paint2_linear_1390_2298" x1="651.578" y1="176.155" x2="608.641" y2="1091.47" gradientUnits="userSpaceOnUse">
          <stop stop-color="rgba(255,255,255,0.5)"></stop>
          <stop offset="1" stop-color="rgba(255,255,255,0.5)" stop-opacity="0.95"></stop>
        </linearGradient>
      </defs>
    </svg>
  </div>
</section>
</template>

<script setup>

  const open = ref(false);
</script>

<style>
.effect-custom div::before,
.effect-custom div::after {
  content: '';
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background: linear-gradient(270deg, #ff8a00, #e52e71, #7d00ff, #00f9ff, #ff8a00);
  background-size: 400% 100%;
  animation: moveLeftRight 5s ease-in-out infinite;
}

.effect-custom div::after {
  filter: blur(10px);
  z-index: -1;
}

.effect-custom:hover > div > span {
  animation-play-state: paused;
}
.bg-custom-gradient {
          background-image: linear-gradient(81deg, #CE1BFB 10.86%, #35E6CC 89.96%);
        }

@keyframes moveLeftRight {
  0%, 100% { transform: translateX(-100%); }
  50% { transform: translateX(100%); }
}

g.eff {
  animation: line-eff 3s infinite;
  transform-origin: 50% 100%;
  filter: blur(70px);
}

.eff-1 {
  animation-delay: 0.3s;
}

.eff-2 {
  animation-delay: 0.5s;
}

.eff-3 {
  animation-delay: 0.7s;
}

@keyframes line-eff {
  0%,
  100% {
    opacity: 0;
    transform: rotate(0) scale(1) translate3d(0, 0, 0);
  }
  50% {
    opacity: 1;
    transform: rotate(0) scale(1) translate3d(0, 0, 300px);
  }
}

</style>
