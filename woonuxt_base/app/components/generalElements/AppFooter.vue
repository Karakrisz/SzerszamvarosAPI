<template>

  
  <footer class=" bg-white">
    <div class="w-full flex footerMain">
      <div class="relative w-[80%] bg-[#F8F8F8] menuPart1">
        <div class="bottomFooterLeft container mx-auto py-4 px-20">
          <div class="grid grid-cols-4 gap-1 bottomFooterLeftMenu">
            <!-- Column 1 - Oldaltérkép -->
            <div>
              <h3 class="font-semibold text-lg mb-4">Oldaltérkép</h3>
              <ul class="space-y-2">
                <li><a href="#" class="hover:text-gray-600">Nyitóoldal</a></li>
                <li><a href="#" class="hover:text-gray-600">Termékek</a></li>
                <li><a href="#" class="hover:text-gray-600">Blog</a></li>
                <li><a href="#" class="hover:text-gray-600">Akciók</a></li>
                <li><a href="#" class="hover:text-gray-600">Ajándékok</a></li>
                <li><a href="#" class="hover:text-gray-600">Márkák</a></li>
                <li><a href="#" class="hover:text-gray-600">Garancia</a></li>
                <li><a href="#" class="hover:text-gray-600">Szállítás</a></li>
              </ul>
            </div>

            <!-- Column 2 - Vásárlói fiók -->
            <div>
              <h3 class="font-semibold text-lg mb-4">Vásárlói fiók</h3>
              <ul class="space-y-2">
                <li><a href="#" class="hover:text-gray-600">Belépés</a></li>
                <li><a href="#" class="hover:text-gray-600">Regisztráció</a></li>
                <li><a href="#" class="hover:text-gray-600">Profilom</a></li>
                <li><a href="#" class="hover:text-gray-600">Kosár</a></li>
                <li><a href="#" class="hover:text-gray-600">Kedvenceim</a></li>
              </ul>
            </div>

            <!-- Column 3 - Információk -->
            <div>
              <h3 class="font-semibold text-lg mb-4">Információk</h3>
              <ul class="space-y-2">
                <li><a href="#" class="hover:text-gray-600">Szerszámváros törzsvásárlói klub</a></li>
                <li><a href="#" class="hover:text-gray-600">Általános szerződési feltételek</a></li>
                <li><a href="#" class="hover:text-gray-600">Adatkezelési tájékoztató</a></li>
                <li><a href="#" class="hover:text-gray-600">Fizetés</a></li>
                <li><a href="#" class="hover:text-gray-600">Szállítás</a></li>
                <li><a href="#" class="hover:text-gray-600">Elérhetőségek</a></li>
                <li><a href="#" class="hover:text-gray-600">Garancia</a></li>
                <li><a href="#" class="hover:text-gray-600">Rólunk</a></li>
                <li><a href="#" class="hover:text-gray-600">Üzletünk</a></li>
                <li><a href="#" class="hover:text-gray-600">Kapcsolat</a></li>
              </ul>
            </div>

            <!-- Column 4 - Kapcsolat -->
            <div class="relative">
              <h3 class="font-semibold text-lg mb-4">Kapcsolat</h3>
              <ul class="space-y-3">
                <li class="flex items-start gap-2">
                  <svg class="w-5 h-5 mt-1 text-red-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/>
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/>
                  </svg>
                  <span>1044 Budapest, Váci út 85-87.</span>
                </li>
                <li class="flex items-center gap-2">
                  <svg class="w-5 h-5 text-red-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/>
                  </svg>
                  <a href="mailto:rendeles@csutakszerszam.hu" class="hover:text-gray-600">rendeles@csutakszerszam.hu</a>
                </li>
                <li class="flex items-center gap-2">
                  <svg class="w-5 h-5 text-red-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
                  </svg>
                  <a href="tel:+36709042097" class="hover:text-gray-600">+36 70 904 2097</a>
                </li>
                <li class="mt-2">
                  <a href="#" class="text-black hover:text-gray-600">
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
                      <path d="M18.77 7.46H14.5v-1.9c0-.9.6-1.1 1-1.1h3V.5h-4.33C10.24.5 9.5 3.44 9.5 5.32v2.15h-3v4h3v12h5v-12h3.85l.42-4z"/>
                    </svg>
                  </a>
                </li>
              </ul>
              <NuxtImg src="/img/webimg/DSS_Icon 1.png" alt="Digital Seed Studio" class="absolute right-0 bottom-0 px-40" />
            </div>
            <!-- Payment and Partner Logos -->
            
          </div>
        </div>
      </div>
      <div class="logoBlock relative w-[20%]">
        <div class="logoBlockInner p-20">
          <ul>
            <li><NuxtImg src="/img/webimg/logo_partner_frame_argep_hu.png" alt="Árgép" class="h-8" /></li>
            <li><NuxtImg src="/img/webimg/logo-120.png" alt="Árukereső" class="h-8" /></li>
            <li><NuxtImg src="/img/webimg/Mastercard-Logo.png" alt="Mastercard" class="h-8" /></li>
            <li><NuxtImg src="/img/webimg/simplepay_otp_en_top.png" alt="Visa" class="h-8" /></li>
          </ul>
        
        
      </div>
      </div>
    </div>
  
  <div class="w-full p-5 bg-red flex justify-center">
  <p class="flex justify-center">
    <NuxtLink to="/" class="shrink-0">
      <NuxtImg src="/img/header/logo.png" class="w-[250px]" />
    </NuxtLink>
  </p>
</div>
</footer>
   
  </template>
  
  <script setup>
  const links = [
    { text: 'Privacy', to: '/privacy' },
    { text: 'Terms', to: '/terms' },
    { text: 'Contact', to: '/contact' }
  ]
  </script>