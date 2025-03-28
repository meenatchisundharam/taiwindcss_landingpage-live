<template>
    <div class="min-h-screen flex items-center justify-center bg-black">
      <div class="relative">
        <!-- Talxwev Text -->
        <div class="text-6xl font-bold text-blue-500 transform rotate-x-20 rotate-y-20">
          <span class="text-white">Talxwev</span>
        </div>
  
        <!-- Contact Details -->
        <div class="text-2xl text-white mt-4 text-center">
          Contact: 99999999
        </div>
  
        <!-- Laser Effect -->
        <div class="absolute top-0 left-0 w-full h-1 bg-red-500 animate-laser"></div>
      </div>
    </div>
  </template>
  
  <style>
  /* Custom Animation for Laser Effect */
  @keyframes laser {
    0% {
      transform: translateX(-100%);
    }
    100% {
      transform: translateX(100%);
    }
  }
  
  .animate-laser {
    animation: laser 2s linear infinite;
  }
  
  /* 3D Effect for Text */
  .rotate-x-20 {
    transform: rotateX(20deg);
  }
  
  .rotate-y-20 {
    transform: rotateY(20deg);
  }
  </style>