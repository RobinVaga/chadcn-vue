<template>
    <nav class="bg-transparent hover:bg-amber-500 px-6 py-4 flex items-center justify-between fixed top-0 left-0 right-0 z-50 border-b border-black-300 ">
      <!-- Logo -->
      <div class="flex items-center space-x-2">
        <p class=" font-bold text-black-600">FYRRE MAGAZINE</p>
      </div>
  
      <!-- Desktop Nav -->
      <div class="hidden md:flex space-x-2">
        <router-link to="/" class="text-black-400 hover:text-black-600">Magazine</router-link>
        <router-link to="/about" class="text-black-400 hover:text-black-600">Author</router-link>
        <router-link to="/contact" class="text-black-400 hover:text-black-600">Podcast</router-link>
        <p class=" text-gray-400"> –– </p>

        <a href="https://instagram.com" target="_blank">
            <img src="../assets/ri_instagram-line.png" alt="Instagram" class="w-4 h-4 rounded-full mt-1.5" />
        </a>

        <a href="https://x.com" target="_blank">
            <img src="../assets/ri_twitter-fill.png" alt="twitter" class="w-4 h-4 rounded-full mt-1.5" />
        </a>

        <a href="https://youtube.com" target="_blank">
            <img src="../assets/ri_youtube-fill.png" alt="youtube" class="w-4 h-4 rounded-full mt-1.5" />
        </a>
        <a href="https://vector.com" target="_blank">
            <img src="../assets/Vector.png" alt="Vector" class="w-3 h-3 mt-2" />
        </a>
    </div>
  
      <!-- Mobile hamburger (optional: toggle menu logic) -->
      <div class="md:hidden">
        <button class="text-gray-700 hover:text-blue-600">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none"
               viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
            <path stroke-linecap="round" stroke-linejoin="round"
                  d="M4 6h16M4 12h16M4 18h16"/>
          </svg>
        </button>
      </div>
    </nav>
  </template>