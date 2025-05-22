<template>
  <section class="hero-section relative w-full min-h-screen bg-cover bg-center text-white">
    <!-- Overlay -->
    <div class="absolute inset-0 bg-black/30 z-0"></div>

    <!-- Content -->
    <div class="relative z-10 flex flex-col items-center justify-center text-center pt-32 px-4 md:px-12">
      <h1 class="text-4xl md:text-6xl font-bold leading-tight">
        Solve problems all <br class="hidden md:block" />
        around the world
      </h1>
      <p class="mt-4 text-lg md:text-xl max-w-2xl">
        Fund and sign campaigns and missions in <br />
        all the 234 countries on the globe
      </p>

      <!-- Get Started Button -->
      <button class="mt-6 bg-lime-500 hover:bg-lime-600 text-white px-6 py-2 rounded-lg font-medium transition">
        Get Started
      </button>
      <p class="mt-3 text-sm text-white">
        Already have an account? <a href="#" class="underline">Log in</a>
      </p>

      <!-- Campaign Card -->
      <div class="mt-12 bg-white text-black rounded-xl shadow-xl p-6 w-full max-w-xl space-y-4">
        <div class="flex items-start gap-4">
          <img src="https://i.pravatar.cc/48" class="rounded-full w-12 h-12" />
          <div>
            <h3 class="font-semibold text-lg">
              Help us Teach English for Kids on China Countryside
            </h3>
            <p class="text-sm mt-1">
              I need about <span class="font-bold">9.000 signatures</span> to deliver to my mayor in two weeks and get that grant!<br />
              Learn more about our project and if you want to see how we are changing lovely children lives on China countryside just teaching how they can use the internet.
            </p>
            <div class="flex items-center text-sm mt-2 space-x-2">
              <span class="text-gray-700 font-medium">Mateus Rodrigues</span>
              <span class="text-gray-400">• São Paulo, Brazil</span>
            </div>
          </div>
        </div>

        <!-- Progress + Action -->
        <div class="flex justify-between items-center">
          <button class="bg-lime-500 hover:bg-lime-600 text-white px-4 py-1.5 rounded-lg text-sm font-medium">
            Sign campaign
          </button>
          <div class="text-sm font-medium text-gray-600">
            4,533 / 9,000
            <div class="w-full bg-gray-200 h-2 rounded mt-1">
              <div class="bg-lime-400 h-2 rounded w-[50%]"></div>
            </div>
          </div>
        </div>
      </div>
    </div>


  </section>
</template>



<style scoped>
.hero-section {
  background-image: url('../assets/Mainpic.png');
}
</style>
