<script setup lang="ts">
import { WishList } from '#components';
import WishListItem from '../WishListItem.vue';


const links = [
  { name: 'AKCIÓK', link: '/' },
  { name: 'Kategóriák', link: '/', prefetch: true },
];
</script>

<template>
  <header class="z-50 sticky top-0">
    <div class="flex justify-between items-center py-4 gap-10 bg-red">
      <div class="container flex justify-between items-center py-4 gap-10 bg-red"> 
        <NuxtLink to="/" class="shrink-0">
          <NuxtImg src="/img/header/logo.png" class="header-logo w-[250px]" />
        </NuxtLink>
        <div class="space-x-8 lg:flex items-center hidden text-white">
          <NuxtImg src="/img/header/phone.svg" class="header-phone w-[20px]" /><span class="left-5">+36 30 636 63 62</span>
          <span>|</span>
          <NuxtImg src="/img/header/EnvelopeSimple.svg" class="header-mail w-[20px]" /><span class="left-5">csutakk75@gmail.com</span>
        </div>
      </div>
    </div>


    
    <div class="flex justify-between items-center py-4 gap-10 bg-white">
  <div class="container mx-auto bg-white px-4">
      <div class="flex items-center justify-between h-16">
        <!-- Mobile Menu -->
        <MenuTrigger class="lg:hidden" />

        <!-- Left side: Navigation -->
        <div class="hidden lg:flex items-center space-x-6">
          <NuxtLink 
            v-for="link in links" 
            :key="link.name" 
            :to="link.link" 
            :class="[
              'header-link',
              link.name === 'AKCIÓK' ? 'text-red-600 font-semibold hover:text-red-700' : 'hover:text-gray-700'
            ]"
          >
            {{ link.name }}
          </NuxtLink>
        </div>

        <!-- Middle: Search Bar -->
        <div class="flex-1 max-w-3xl mx-6">
          <ProductSearch class="rounded-full p-2 shadow-[0_0_5px_4px_#e9e9e9]">
          </ProductSearch>
        </div>

        <!-- Right side: Icons -->
        <div class="flex items-center space-x-6">
          <SignInLink class="rounded-full p-2 shadow-[0_0_5px_4px_#e9e9e9]" />
          <!-- Heart icon placeholder -->
           
          <button class="hover:text-gray-700">
            <!-- Heart icon will be added later -->
          </button>
          <CartTrigger class="rounded-full p-2 shadow-[0_0_5px_4px_#e9e9e9]" />
        </div>
      </div>
    </div>
</div>
    
  </header>
</template>
