<template>
 <section class="relative overflow-hidden callToAction">
  <!-- Background with diagonal cut -->
  <div class="relative">
    <!-- Blue background section -->
    <div class="bg-[#4086F4] py-20 md:py-32 relative ctablue">
      <div class="container mx-auto px-4 cta1">
        <div class="max-w-xl">
          <!-- Main heading -->
          <h1 class="text-white text-4xl md:text-5xl font-bold leading-tight mb-6">
            Válassz minőségi szerszámot és használd egy életen keresztül!
          </h1>
          
          <!-- Description text -->
          <p class="text-white/90 text-lg mb-8 leading-relaxed">
            Ne köss kompromisszumot, ha szerszámokról van szó! Válaszd azokat az eszközöket, amelyek hosszú távon is bírják a terhelést, és biztosítják a stabil, megbízható teljesítményt minden alkalommal. Mert a minőség mindig megtérül.
          </p>
          
          <!-- CTA Button -->
          <button class="bg-white text-gray-800 px-8 py-3 rounded-lg font-medium hover:bg-sky-700 color-white transition-colors">
            Fedezd fel a prémium szerszámokat
          </button>
        </div>
      </div>
    </div>

    <!-- Diagonal white overlay -->
    <div class="absolute top-0 right-0 h-full w-1/3 lg:w-1/2 ctadiagonalwhite">
      <div class="h-full w-full bg-white transform -skew-x-12 origin-top-right translate-x-1/4"></div>
    </div>
  </div>

  <!-- Image placeholder -->
  <div class="absolute top-1/2 right-0 transform -translate-y-1/2 w-1/2 hidden md:block ctadiagonal">
    <NuxtImg 
      src="/img/webimg/hands.png" 
      alt="Hand holding pliers" 
      class="w-full h-full object-contain"
    />
  </div>
</section>
</template>

