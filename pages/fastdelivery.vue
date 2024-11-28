<template>
  <nav class="py-3 sm:mx-3 bg-white border-b border-gray-100 sticky top-0 z-50">
  <div class="container md:px-12 md:flex md:justify-between md:items-center">
         <div class="flex items-center justify-between" >
           <a href="#" class="flex items-center text-green-900 text-3xl md:mr-3"><i class="fa-solid fa-bolt"></i><span class="text-gray-900"> fast</span>
            <span class="text-3xl text-gray-900 font-sans font-bold">Delivery</span>
           </a>
           <span class=" block mx-2 text-3xl bg-gray-100 p-2 rounded-lg md:hidden">
             <svg name="menu" @click="toggleMenu" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.7" stroke="currentColor" class="w-6 h-6">
            <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"/>
            </svg>
           </span>
         </div>
        <div>
          <ul :class="{ 'top-[80px] opacity-100': isMenuOpen, 'opacity-0 top-[-400px]': !isMenuOpen }" class="p-5 z-10 absolute bg-white/80 backdrop-blur w-full left-0 py-4 opacity-0 top-[-400px] transition-all ease-in duration-500 md:p-0 md:flex md:items-center md:static md:w-auto md:opacity-100">
         <li class="md:my-0">
           <a href="#home" class="font-medium duration-500 text-gray-700 hover:text-gray-400">Home</a>
         </li>
         <li class="my-6 md:my-0">
           <a href="#Service" class="font-medium duration-500 text-gray-700 hover:text-gray-400">Service</a>
         </li>
         <li class="my-6 md:my-0">
           <a href="#Pricing" class="font-medium duration-500 text-gray-700 hover:text-gray-400">Pricing</a>
         </li>
         <li class="my-6 md:my-0">
           <a href="#Blog" class="font-medium duration-500 text-gray-700 hover:text-gray-400">Blog</a>
         </li>
         <li class="my-6 md:my-0">
           <a href="#Login" class="font-medium duration-500 text-gray-700 hover:text-gray-400">Login</a>
         </li>
         <a href="#"> <button type="button" class="w-full text-white bg-green-800 font-medium rounded-lg px-3.5 py-2.5 text-center hover:bg-green-500 hover:drop-shadow-md transition duration-400 ease-in-out">Get Started</button></a>
         </ul>
        </div>
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
    <button type="button" class="text-white bg-green-800 font-medium rounded-lg px-5 py-4 text-center hover:bg-green-700 hover:drop-shadow-md transition duration-300 ease-in-out">Get Started</button>
  </div>
  </div>
  <div class="lg:w-96 sm:w-96 sm:px-5 lg:pr-8">
  <img class="ml-auto rounded-lg" src="https://plus.unsplash.com/premium_photo-1682142902305-b2d1aacac666?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D">
  </div>
</div>
<div class="mx-auto mb-12 bg-green-100 w-full py-20 lg:-mt-5">
  <div class="grid grid-cols-1 place-items-center md:grid-cols-3 lg:grid-cols-3 gap-8">
    <div class="flex items-center justify-between">
      <i class="fa-solid fa-box text-2xl m-2"></i>
      <h1 class="text-3xl font-medium text-green-800">Job<span class="text-3xl font-extrabold text-green-800">board</span></h1>
    </div>
        <h1 class="text-3xl font-medium text-green-800">Pathway</h1>

       <h1 class="text-3xl text-green-800">dro<span class="text-3xl font-extrabold text-green-800">ps.</span></h1>
     <div>
      <span class="text-3xl font-extrabold text-green-800">// Air</span>
     <span class="text-3xl text-green-800 font-none">stream</span>
    </div>    
    <h1 class="text-3xl font-medium text-green-800">Pathway</h1>
  </div>
</div>
</section>

<section id="Service" class="py-5">
  <div class="container mx-auto">
    <div class="text-center">
      <h1 class="p-1 text-2xl font-semibold sm:text-3xl md:text-4xl md:p-2 lg:text-4xl lg:p-2">Amazing Features</h1>
      <p class="text-gray-600 lg:text-xl">We are mmitted to a unique, cutting-edge approach to that</p>
    </div>
    <div class="mt-10 m-3 sm:mt-12 md:mt-16 lg:mt-20 md:m-5 lg:m-7 grid place-items-center grid-cols-1 md:grid-cols-2 lg:grid-cols-2 gap-7">
      <div class="text-center">
        <div>
          <i class="fa-solid fa-graduation-cap text-4xl text-green-800"></i>
        </div>
        <h3 class="p-2 text-xl font-medium">Collection of textile</h3>
        <p class="text-gray-600">One morning, when Gregor Samsa woke from troubled dreams, he found himself It showed transformed.</p>
      </div>
      <div class="text-center">
        <div>
          <i class="fa-solid fa-code-fork text-4xl text-green-800"></i>
        </div>
        <h3 class="p-2 text-xl font-medium">Collection of textile</h3>
        <p class="text-gray-600">One morning, when Gregor Samsa woke from troubled dreams, he found himself It showed transformed.</p>
      </div>
      <div class="text-center">
        <div>
          <i class="fa-regular fa-message text-4xl text-green-800"></i>
        </div>
        <h3 class="p-2 text-xl font-medium">Collection of textile</h3>
        <p class="text-gray-600">One morning, when Gregor Samsa woke from troubled dreams, he found himself It showed transformed.</p>
      </div>
      <div class="text-center">
        <div>
          <i class="fa-solid fa-flask text-4xl text-green-800"></i>
        </div>
        <h3 class="p-2 text-xl font-medium">Collection of textile</h3>
        <p class="text-gray-600">One morning, when Gregor Samsa woke from troubled dreams, he found himself It showed transformed.</p>
      </div>
      <div class="text-center">
        <div>
          <i class="fa-solid fa-suitcase text-4xl text-green-800"></i>
        </div>
        <h3 class="p-2 text-xl font-medium">Collection of textile</h3>
        <p class="text-gray-600">One morning, when Gregor Samsa woke from troubled dreams, he found himself It showed transformed.</p>
      </div>
      <div class="text-center">
        <div>
          <i class="fa-solid fa-circle-half-stroke text-4xl text-green-800"></i>
        </div>
        <h3 class="p-2 text-xl font-medium">Collection of textile</h3>
        <p class="text-gray-600">One morning, when Gregor Samsa woke from troubled dreams, he found himself It showed transformed.</p>
      </div>
    </div>
  </div>
</section>

<section id="" class="bg-blue-50 z-0 lg:py-5">
  <div class="py-10 text-center">
    <h1 class="text-2xl font-bold md:text-3xl lg:text-4xl">Our recent work</h1>
    <p class="p-3">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Amet, vitae.</p>
  </div>
    <div class="flex items-center justify-center md:p-6 lg:p-10">
  <div class="grid grid-flow grid-cols-1 lg:grid-rows-2 md:grid-cols-3 lg:grid-cols-3 gap-6">
    <div class="group relative items-center justify-center overflow-hidden cursor-pointer hover:shadow-xl hover:shadow-black/60 transition-shadow">
      <div class="h-96 w-72">
        <img class="h-full w-full object-cover group-hover: rotate-3 group-hover:scale-125 transition-transform duration-500" src="https://images.unsplash.com/photo-1487611459768-bd414656ea10?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D">
      </div>
      <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-black group-hover:from-black/70 group-hover:via-black/60 group-hover:to-black/70"></div>
      <div class="absolute inset-0 flex flex-col items-center justify-center px-9 text-center translate-y-[60%] group-hover:translate-y-0 transition-all">
        <h1 class="text-3xl font-bold text-white">Collection of textile</h1>
        <p class="text-lg italic text-white mb-3 opacity-0 group-hover:opacity-100 transition-opacity duration-300">One morning, when Gregor Samsa woke from troubled dreams, he found himself It showed transformed.</p>
        <button class="rounded-full shadow shadow-black/50 bg-neutral-900 py-2 px-3.5 text-md capitalize text-white">See more</button>
      </div>
    </div>
    <div class="group relative items-center justify-center overflow-hidden cursor-pointer hover:shadow-xl hover:shadow-black/60 transition-shadow">
      <div class="h-96 w-72">
        <img class="h-full w-full object-cover group-hover: rotate-2 group-hover:scale-100 transition-transform duration-500" src="https://plus.unsplash.com/premium_photo-1661270506468-b81997c3bcc8?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D">
      </div>
      <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-black group-hover:from-black/70 group-hover:via-black/60 group-hover:to-black/70"></div>
      <div class="absolute inset-0 flex flex-col items-center justify-center px-9 text-center translate-y-[60%] group-hover:translate-y-0 transition-all">
        <h1 class="text-3xl font-bold text-white">How about sleep a little bit</h1>
        <p class="text-lg italic text-white mb-3 opacity-0 group-hover:opacity-100 transition-opacity duration-300">Doing business like this takes much more effort than doing your own business at home, and on top.</p>
        <button class="rounded-full shadow shadow-black/50 bg-neutral-900 py-2 px-3.5 text-md capitalize text-white">See more</button>
      </div>
    </div>
    <div class="group relative items-center justify-center overflow-hidden cursor-pointer hover:shadow-xl hover:shadow-black/60 transition-shadow">
      <div class="h-96 w-72">
        <img class="h-full w-full object-cover group-hover: rotate-3 group-hover:scale-125 transition-transform duration-500" src="https://images.unsplash.com/photo-1526657782461-9fe13402a841?q=80&w=1384&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D">
      </div>
      <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-black group-hover:from-black/70 group-hover:via-black/60 group-hover:to-black/70"></div>
      <div class="absolute inset-0 flex flex-col items-center justify-center px-9 text-center translate-y-[60%] group-hover:translate-y-0 transition-all">
        <h1 class="text-3xl font-bold text-white">Collection of textile</h1>
        <p class="text-lg italic text-white mb-3 opacity-0 group-hover:opacity-100 transition-opacity duration-300">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt aliquam qui assumenda </p>
        <button class="rounded-full shadow shadow-black/50 bg-neutral-900 py-2 px-3.5 text-md capitalize text-white">See more</button>
      </div>
    </div>
    <div class="group relative items-center justify-center overflow-hidden cursor-pointer hover:shadow-xl hover:shadow-black/60 transition-shadow">
      <div class="h-96 w-72">
        <img class="h-full w-full object-cover group-hover: rotate-3 group-hover:scale-125 transition-transform duration-500" src="https://plus.unsplash.com/premium_photo-1661281205207-35cff1245a97?q=80&w=1469&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D">
      </div>
      <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-black group-hover:from-black/70 group-hover:via-black/60 group-hover:to-black/70"></div>
      <div class="absolute inset-0 flex flex-col items-center justify-center px-9 text-center translate-y-[60%] group-hover:translate-y-0 transition-all">
        <h1 class="text-3xl font-bold text-white">But who knows, would do it</h1>
        <p class="text-lg italic text-white mb-3 opacity-0 group-hover:opacity-100 transition-opacity duration-300">You've got to get enough sleep. Other travelling salesmen live a life of luxury. For instance. </p>
        <button class="rounded-full shadow shadow-black/50 bg-neutral-900 py-2 px-3.5 text-md capitalize text-white">See more</button>
      </div>
    </div>
    <div class="group relative items-center justify-center overflow-hidden cursor-pointer hover:shadow-xl hover:shadow-black/60 transition-shadow">
      <div class="h-96 w-72">
        <img class="h-full w-full object-cover group-hover: rotate-3 group-hover:scale-125 transition-transform duration-500" src="https://plus.unsplash.com/premium_photo-1678752716927-44f989df7655?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MjV8fGxhcHRvcHxlbnwwfHwwfHx8MA%3D%3D">
      </div>
      <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-black group-hover:from-black/70 group-hover:via-black/60 group-hover:to-black/70"></div>
      <div class="absolute inset-0 flex flex-col items-center justify-center px-9 text-center translate-y-[60%] group-hover:translate-y-0 transition-all">
        <h1 class="text-3xl font-bold text-white">How about sleep a little bit</h1>
        <p class="text-lg italic text-white mb-3 opacity-0 group-hover:opacity-100 transition-opacity duration-300">Doing business like this takes much more effort than doing your own business at home, and on top.</p>
        <button class="rounded-full shadow shadow-black/50 bg-neutral-900 py-2 px-3.5 text-md capitalize text-white">See more</button>
      </div>
    </div>
  </div>
</div>
</section>

<section id="Blog" class="p-10 md:p-3 lg:p-5">
  <div class="p-10 text-center px-5">
    <h1 class="text-2xl font-medium md:text-4xl lg:text-4xl">FastDelivery explained</h1>
    <p class="p-3 text-gray-500 lg:text-lg">We are committed to a unique, cutting-edge approach to that</p>
  </div>
<div class="bg-green-200 text-left p-8 md:ml-28 md:mr-28 lg:ml-56 lg:mr-56">
    <h1 class="text-lg text-green-900 font-bold">In enim justo, rhoncus ut, imperdiet a, venenatis</h1>
    <p class="py-4 text-gray-600 text-lg">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu.</p>
    <p class="py-4 text-gray-600 text-lg">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient </p>
  </div>
  <div class="mt-5 py-4 bg-green-200 p-8 md:ml-28 md:mr-28 lg:ml-56 lg:mr-56">
    <h1 class="text-xl text-green-900 font-bold">In enim justo, rhoncus ut, imperdiet a, venenatis</h1>
    <p class="py-4 text-gray-600 text-lg">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis.</p>
  </div>
</section>

<section id="Pricing" class=" bg-blue-50 py-12 lg:py-20">
  <div class="text-center py-8 px-5 md:py-24">
    <h1 class="text-xl font-medium md:text-4xl">Simple pricing plans</h1>
    <p class="p-3 text-lg text-gray-600 md:text-xl">We are committed to a unique, cutting-edge approach to that</p>
  </div>
  <div class="px-14 ml-28 mr-28">
    <div class="grid md:grid-cols-3 md:gap-2 lg:grid-cols-3 gap-5 lg:gap-2">
      <div class="shadow-xl rounded-lg py-8 px-8 text-center bg-white">
        <div class="flex justify-center items-center">
            <i class="fa-solid fa-user-graduate text-3xl text-green-800"></i>
        </div>
        <span class="text-xl font-medium md:text-2xl">Freelance coaching</span>
        <p class="mt-1 text-gray-600 md:text-lg">For single entrepreneurs</p>
        <h3 class="py-4 text-2xl font-bold text-green-900 md:text-3xl">€119 p/m</h3>
        <hr class="my-4 border-gray-400 w-full">
        <ul>
          <li class="py-1 text-lg text-gray-600">20 hours</li>
          <li class="py-1 text-lg text-gray-600">Email support</li>
          <li class="text-lg text-gray-600">Phone support</li>
          <li class="py-1 text-lg text-gray-600">Work from home</li>
          <li class="py-1 text-lg text-gray-600">12 months</li>
        </ul>
        <button class="bg-green-900 text-white text-lg py-2 px-3 rounded-lg mt-5 hover:bg-green-700">Get started</button>
      </div>
      <div class="shadow-xl rounded-lg py-8 px-8 text-center bg-white md:transform md:scale-125 lg:transform lg:scale-110">
        <div class="flex justify-center items-center">
            <i class="fa-solid fa-suitcase text-3xl text-green-800"></i>
        </div>
        <span class="text-xl font-medium md:text-2xl">Team coaching</span>
        <p class="mt-1 text-gray-600 md:text-lg">For more entrepreneurs</p>
        <h3 class="py-4 text-2xl font-bold text-green-900 md:text-3xl">€249 p/m</h3>
        <hr class="my-4 border-gray-400 w-full">
        <ul>
          <li class="py-1 text-lg text-gray-600">20 hours</li>
          <li class="py-1 text-lg text-gray-600">Email support</li>
          <li class="text-lg text-gray-600">Phone support</li>
          <li class="py-1 text-lg text-gray-600">Work from home</li>
          <li class="py-1 text-lg text-gray-600">12 months</li>
        </ul>
        <button class="bg-green-900 text-white text-lg py-2 px-3 rounded-lg mt-5 hover:bg-green-700">Get started</button>
      </div>
      <div class="shadow-xl rounded-lg py-8 px-8 text-center bg-white">
        <div class="flex justify-center items-center">
            <i class="fa-solid fa-truck-fast text-3xl text-green-800"></i>
        </div>
      <span class="text-xl font-medium md:text-2xl">Pro coaching</span>
        <p class="mt-1 text-gray-600 md:text-lg">For many entrepreneurs</p>
        <h3 class="py-4 text-2xl font-bold text-green-900 md:text-3xl">€489 p/m</h3>
        <hr class="my-4 border-gray-400 w-full">
        <ul>
          <li class="py-1 text-lg text-gray-600">20 hours</li>
          <li class="py-1 text-lg text-gray-600">Email support</li>
          <li class="text-lg text-gray-600">Phone support</li>
          <li class="py-1 text-lg text-gray-600">Work from home</li>
          <li class="py-1 text-lg text-gray-600">12 months</li>
        </ul>
        <button class="bg-green-900 text-white text-lg py-2 px-3 rounded-lg mt-5 hover:bg-green-700">Get started</button>
      </div>
    </div>
  </div>
</section>

<section class="bg-gray-50">
  <footer class="bg-gray-50 text-gray-800 py-20 sm:py-12">
    <div class=" ml-2 px-4 mb-4">
      <a href="#" class="flex items-center text-green-900 text-2xl">
        <i class="fa-solid fa-bolt ml-2"></i>
        <span class="text-gray-900 ml-1"> fast</span>
        <span class="lg:text-2xl text-gray-900 font-sans font-bold">Delivery</span>
      </a>
    </div>
    <div class="px-8 mt-20">
      
      <div class="flex flex-wrap justify-between">
        <!-- Company Section -->
        <div class="w-full md:w-1/4 mb-4">
          <h5 class="font-medium mb-2 text-xl">Company:</h5>
          <ul class="md:grid md:gap-3">
            <li><a href="#" class="hover:text-gray-400">Landingpages</a></li>
            <li><a href="#" class="hover:text-gray-400">Features</a></li>
            <li><a href="#" class="hover:text-gray-400">Download brochure</a></li>
          </ul>        
        </div>
        <!-- hr -->
         <div class="block md:hidden w-full bg-gray-300 h-0.5 my-4"></div>
        <div class="hidden md:block w-0.5 bg-gray-300 mx-4"></div>
        <!-- Industries Section -->
        <div class="w-full sm:w-1/2 md:w-1/4 mb-4">
          <h5 class="font-medium mb-2 text-xl">Industries:</h5>
          <ul class="md:grid md:grid-cols-2 md:gap-3">
            <li><a href="#" class="hover:text-gray-400">Employment</a></li>
            <li><a href="#" class="hover:text-gray-400">Company</a></li>
            <li><a href="#" class="hover:text-gray-400">Childcare</a></li>
            <li><a href="#" class="hover:text-gray-400">Download brochure</a></li>
          </ul>
        </div>
        <!-- hr -->
         <div class="block md:hidden w-full bg-gray-300 h-0.5 my-4"></div>
        <div class="hidden md:block w-0.5 bg-gray-300 mx-4"></div>
        <!-- Follow Us Section -->
        <div class="w-full md:w-1/4 mb-4">
          <h5 class="font-medium mb-2 text-xl">Follow us:</h5>
          <ul class="md:grid md:grid-cols-2 md:gap-3">
            <li><a href="#"><i class="fa-brands fa-twitter text-green-700 text-xl"></i> <span class="hover:text-gray-400 ml-1">Twitter</span></a></li>
            <li><a href="#"><i class="fa-brands fa-instagram text-green-700 text-xl"></i> <span class="hover:text-gray-400 ml-1">Instagram</span></a></li>
            <li><a href="#"><i class="fa-brands fa-facebook text-green-700 text-xl"></i> <span class="hover:text-gray-400 ml-1">Facebook</span></a></li>
          </ul>
        </div>
      </div>
      <!-- Cookie Settings and Copyright -->
      <div class="border-t-2 border-gray-200 mt-8 pt-4 text-sm flex flex-col sm:flex-row sm:justify-between text-center sm:text-left">
        <p><a href="#" class="hover:text-gray-300">Cookie settings</a></p>
        <p class="sm:mt-0">&copy;2021 Company. All rights reserved.</p>
      </div>
    </div>
  </footer>
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