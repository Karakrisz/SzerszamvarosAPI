<template>

<section class="relative">
  <!-- Main container with yellow and black background -->
  <div class="flex p-[100px] bg-[#F8F8F8] blockNews">
    <!-- Left side - Yellow section (70%) -->
    <div class="w-[70%] bg-[#F8C05A] py-20 px-24 blockNewsForm">
      <h2 class="text-[28px] font-medium mb-8">
        Iratkozz fel hírlevelünkre és maradj naprakész!
      </h2>

      <form class="max-w-[600px] space-y-4">
        <!-- Name Input -->
        <input 
          type="text" 
          placeholder="Név" 
          class="w-full px-6 py-4 rounded-full bg-white text-gray-600 placeholder-gray-400 focus:outline-none"
        >

        <!-- Email Input -->
        <input 
          type="email" 
          placeholder="E-mail cím" 
          class="w-full px-6 py-4 rounded-full bg-white text-gray-600 placeholder-gray-400 focus:outline-none"
        >

        <!-- Checkbox -->
        <div class="flex items-start gap-3 mt-6">
          <input 
            type="checkbox" 
            id="privacy"
            class="mt-1.5 h-4 w-4 rounded border-gray-300"
          >
          <label for="privacy" class="text-[15px]">
            Hozzájárulok az adataim kezeléséhez és elfogadom az 
            <a href="#" class="underline hover:text-gray-800">Adatkezelési tájékoztatót</a>.
          </label>
        </div>

        <!-- Submit Button -->
        <button 
          type="submit" 
          class="bg-black text-white px-8 py-3 rounded flex items-center gap-2 hover:bg-black/90 transition-colors mt-6"
        >
          Küldés
          
        </button>
      </form>
    </div>

    <!-- Right side - Black section (30%) -->
    <div class="w-[30%] bg-black">
      
    </div>


  </div>
</section>
</template>

