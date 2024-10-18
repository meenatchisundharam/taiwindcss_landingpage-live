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

<section id="Home" class="bg-blue-50 overflow-hidden">
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


<section id="Service" class="py-12">
  <div class="px-5 text-center">
    <h1 class="text-xl font-bold text-blue-500 md:text-3xl lg:text-3xl xl:text-4xl">Amazing Features</h1>
    <p class="py-2 text-lg text-gray-600 xl:text-2xl">We are mmitted to a unique, cutting-edge approach to that</p>
  </div>
   <div class="py-10 grid md:grid-cols-2 lg:grid-cols-2">
     <div class="px-10 py-5 flex gap-5">
         <i class="fa-solid fa-folder text-3xl text-blue-500 xl:text-4xl"></i>
         <div class="text-left">
         <h1 class="text-gray-600 font-medium text-lg xl:text-xl">A collection of textile samples</h1>
         <p class="py-2 text-gray-900">One morning, when Gregor Samsa woke from troubled dreams, he found himself It showed transformed in his bed into a horrible vermin.</p>
         </div>
       </div>
       <div class="px-10 py-5 flex gap-5">
         <i class="fa-solid fa-file text-3xl text-blue-500 xl:text-4xl"></i>
         <div class="text-left">
         <h1 class="text-gray-600 font-medium text-lg xl:text-xl">How about if I sleep a little bit</h1>
         <p class="py-2 text-gray-900">Doing business like this takes much more effort than doing your own business at home, and on top of that there's the curse of travelling.</p>
         </div>
       </div>
       <div class="px-10 py-5 flex gap-5">
         <i class="fa-solid fa-database text-3xl text-blue-500 xl:text-4xl"></i>
         <div class="text-left">
      <h1 class="text-gray-600 font-medium text-lg xl:text-xl">He felt a slight itch up on his bell</h1>
         <p class="py-2 text-gray-900">He must have tried it a hundred times, shut his eyes so that he wouldn't have to look at the floundering legs, and only stopped when.</p>
         </div>
       </div>
       <div class="px-10 py-5 flex gap-5">
         <i class="fa-solid fa-cloud-arrow-down text-3xl text-blue-500 xl:text-4xl"></i>
         <div class="text-left">
         <h1 class="text-gray-600 font-medium text-lg xl:text-xl">But who knows, maybe that would do it</h1>
         <p class="py-2 text-gray-900">You've got to get enough sleep. Other travelling salesmen live a life of luxury. For instance, whenever I go back to the guest.</p>
         </div>
       </div>
   </div>
   <div class="py-3 md:flex md:py-14 lg:flex">
     <div class="">
       <img src="https://images.unsplash.com/photo-1508873699372-7aeab60b44ab?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="credits:unsplash.com" class="p-5 rounded-e-full md:py-8">
     </div>
     <div class="px-5 py-3 md:py-2">
       <h1 class="text-xl text-gray-900 font-bold md:text-2xl lg:text-3xl xl:text-4xl">So if on advanced addition absolute received replying</h1>
       <p class="py-6 text-lg text-gray-500">When, while the lovely valley teems with vapour around me, and the meridian sun strikes the waiting be females upper surface of the impenetrable foliage of my trees</p>
       <p class="py-3 text-lg text-gray-500">End why melancholy estimating her had indulgence bachelor domestic extended middletons. Say ferrars demands besides her address. Blind going you merit few fancy their.</p>
       <p class="py-3 text-lg text-gray-500">On could my in order never it. Or excited certain sixteen it to parties colonel. Law gate lif On nature or no.</p>
     </div>
   </div>

   <div class="py-3 md:flex md:py-14 lg:flex">
     <div class="md:order-2">
       <img src="https://images.unsplash.com/photo-1508873699372-7aeab60b44ab?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="credits:unsplash.com" class="p-5 rounded-s-full md:py-8">
     </div>
     <div class="px-5 py-3 md:py-px">
       <h1 class="text-xl text-gray-900 font-bold md:text-2xl lg:text-3xl xl:text-4xl">So if on advanced addition absolute received replying</h1>
       <p class="py-6 text-lg text-gray-500">When, while the lovely valley teems with vapour around me, and the meridian sun strikes the waiting be females upper surface of the impenetrable foliage of my trees</p>
       <p class="py-3 text-lg text-gray-500">End why melancholy estimating her had indulgence bachelor domestic extended middletons. Say ferrars demands besides her address. Blind going you merit few fancy their.</p>
       <p class="py-3 text-lg text-gray-500">On could my in order never it. Or excited certain sixteen it to parties colonel. Law gate lif On nature or no.</p>
     </div>
   </div>
</section>

<section id="Price" class="">
  <div class="p-5 bg-gray-100 relative">
    <div class="shadow-xl rounded-xl bg-white -mt-10 relative md:ml-44 md:mr-52 xl:ml-96 xl:mr-96 xl:py-5">
      <div class="text-center -mt-5"> 
        <span class="px-10 py-10 bg-blue-500 rounded-full"><i class="fa-solid fa-cube text-3xl text-white font-semibold"></i></span>
      </div>
      <div class="p-5 text-center mt-5">
        <h1 class="py-3 text-xl font-medium lg:text-4xl">€28 per month</h1>
        <p class="text-lg text-gray-500 lg:text-xl">We are committed to a unique, cutting-edge</p>
         <span class="">
            <button class="mt-5 px-4 py-4 bg-blue-500 w-full rounded-lg text-white font-medium hover:bg-blue-400 lg:w-80">Order now</button>
         </span>
      </div>
      <div class="px-5 py-5 md:flex md:gap-16">
        <div class="lg:ml-12 xl:ml-3">
        <p class="py-2 text-gray-500 font-medium">&#10003 Everyone realizes why</p>
        <p class="py-2 text-gray-500 font-medium">&#10003 To achieve this, it would</p>
        <p class="py-2 text-gray-500 font-medium">&#10003 Now residence dashwoods</p>
        <p class="py-2 text-gray-500 font-medium">&#10003 Remember outweigh do</p>
      </div>
      <div class="">
        <p class="py-2 text-gray-800 font-medium">&#10003 Breakfast as</p>
        <p class="py-2 text-gray-800 font-medium">&#10003 Must you with him</p>
        <p class="py-2 text-gray-800 font-medium">&#10003 Behind sooner dining</p>
        <p class="py-2 text-gray-800 font-medium">&#10003 brother believe an</p>
      </div>
      </div>
    </div>
    <div class="mx-auto w-full py-20 lg:-mt-5">
  <div class="grid grid-cols-1 place-items-center md:grid-cols-3 lg:grid-cols-3 gap-8">
    <div class="flex items-center justify-between">
      <i class="fa-solid fa-box text-gray-400 text-2xl px-3 xl:text-3xl"></i>
      <h1 class="text-3xl font-medium text-gray-400 xl:text-4xl">Job<span class="text-3xl font-extrabold text-gray-400 xl:text-4xl">board</span></h1>
    </div>
      <h1 class="text-3xl font-medium text-gray-400">Pathway</h1>
      <div>
      <span class="text-3xl font-extrabold text-gray-400 xl:text-4xl">// Air</span>
      <span class="text-3xl text-gray-400 font-medium xl:text-4xl">stream</span>
    </div> 
      <h1 class="text-3xl text-gray-400">dro<span class="text-3xl font-extrabold text-gray-400">ps.</span></h1>   
      <p class="flex items-center text-gray-400 text-3xl md:mr-3">
      <i class="fa-solid fa-bolt"></i>
      <span class="text-gray-400 xl:text-4xl"> fast</span>
      <span class="text-3xl text-gray-400 font-sans font-bold xl:text-4xl">Delivery</span>
           </p> 
         </div>
     </div>
  </div>
</section>

<footer class="px-7 bg-slate-800 text-white py-10">
  <div class="lg:grid lg:grid-cols-2 gap-10">
    <div class="py-10">
      <h1 class="text-2xl font-bold text-white">pathway</h1>
      <p class="py-8 text-gray-400 lg:text-lg text-left">Promise your reader something valuable. Will you teach her how to learn a new skill? <span>Will you persuade her to do something she’s never done before?</span></p>
        <i class="fa-brands fa-facebook text-gray-400 text-3xl hover:text-white lg:py-5"></i>
        <i class="fa-brands fa-instagram px-7 text-gray-400 text-3xl hover:text-white"></i>
        <i class="fa-brands fa-twitter text-gray-400 text-3xl hover:text-white"></i>
      <p class="text-sm mt-5 xl:py-6">©2021 Company. All rights reserved.</p>
    </div>
    <div class="lg:py-10 grid gap-10 grid-cols-2 md:grid-cols-2 lg:grid-cols-2 xl:grid-cols-2">
      <div class="flex flex-col">
        <h1 class="mb-3 text-xl text-gray-300 font-bold">Product</h1>
        <a href="#" class=" lg:py-2 hover:text-gray-400">Landingpages</a>
        <a href="#" class=" lg:py-2 hover:text-gray-400">Features</a>
        <a href="#" class="lg:py-2 hover:text-gray-400">Documentation</a>
      </div>
      <div class="flex flex-col">
        <h1 class="mb-3 text-xl text-gray-300 font-bold">Industries</h1>
        <a href="#" class="lg:py-2 hover:text-gray-400">Employment</a>
        <a href="#" class="lg:py-2 hover:text-gray-400">Childcare</a>
        <a href="#" class="lg:py-2 hover:text-gray-400">Education</a>
      </div>
      <div class="flex flex-col">
        <h1 class="mb-3 text-xl text-gray-300 font-bold">About us</h1>
        <a href="#" class="lg:py-2 hover:text-gray-400">Company</a>
        <a href="#" class="lg:py-2 hover:text-gray-400">Download brochure</a>
        <a href="#" class="lg:py-2 hover:text-gray-400">Media Kit</a>
      </div>
      <div class="flex flex-col">
        <h1 class="mb-3 text-xl text-gray-300 font-bold">Legal</h1>
        <a href="#" class="lg:py-2 hover:text-gray-400">Terms and conditions</a>
        <a href="#" class="lg:py-2 hover:text-gray-400">Security</a>
        <a href="#" class="lg:py-2 hover:text-gray-400">Privacy and Cookie Statement</a>
      </div>
    </div>
  </div>
</footer>
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