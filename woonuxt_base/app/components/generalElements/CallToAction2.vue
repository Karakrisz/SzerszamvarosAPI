<template>

<section class="relative overflow-hidden">
  <!-- Main container -->
  <div class="flex min-h-[600px] ctablockyellow">
    <!-- Left section with image -->
    <div class="relative w-[55%] bg-gradient-to-b from-white from-[40%] to-[#1a1a1a] to-[40%] ctaleftyellow">

      <!-- Black background -->
      
      <!-- Image -->
      <NuxtImg 
        src="/img/webimg/worker.png" 
        alt="Senior craftsman with safety glasses" 
        class="relative z-10 h-full object-contain workImgBlack"
      />
    </div>

    <!-- Right section -->
    <div class="relative w-[45%] bg-[#F8C05A] ctarightyellow">
      <!-- Yellow background with diagonal cut -->
      <div class="absolute inset-0 bg-[#F8C05A] yellowSkew"></div>
      <!-- White diagonal overlay -->

      <!-- Content container -->
      <div class="relative z-10 pt-20 pr-20 pl-16 ctayellowblkr">
        <h2 class="text-[40px] font-bold mb-6">
          Sosem késő elkezdeni!
        </h2>
        
        <p class="text-lg leading-relaxed mb-8">
          Az alkotás öröme nem korhoz kötött! Legyél fiatal vagy idősebb, mindig itt a lehetőség, hogy új dolgokat tanulj, szerelj és alkoss. Könnyen használható, megbízható szerszámainkkal segítünk, hogy bármely életkorban magabiztosan vághass bele a barkácsolás világába.
        </p>
        
        <button class="bg-[#222222] text-white px-8 py-3 rounded">
          Kezdd el most
        </button>
      </div>

    </div>
  </div>
</section>
</template>

