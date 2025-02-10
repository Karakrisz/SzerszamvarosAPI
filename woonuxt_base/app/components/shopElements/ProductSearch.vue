<script setup>
import { ref, watch } from 'vue'

const { getSearchQuery, setSearchQuery, clearSearchQuery } = useSearching()
const searchQuery = ref(getSearchQuery())

const reset = () => {
  clearSearchQuery()
  searchQuery.value = ''
}

watch(getSearchQuery, (value) => {
  if (!value) reset()
})

const handleSubmit = () => {
  setSearchQuery(searchQuery.value)
}
</script>

<template>
  <form class="relative items-center" @submit.prevent="handleSubmit">
    <input 
      v-model="searchQuery" 
      type="text" 
      :placeholder="$t('messages.shop.searchProducts')"
      class="z-0 inline-flex items-center w-full px-10 py-2 text-sm text-gray-500 border border-gray-200 border-none rounded-full focus:border-none focus:border-gray-300"
    >
    <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none">
      <Icon 
        name="ph:magnifying-glass" 
        size="20"
        class="text-red-600" 
      />
    </div>
    <span 
      v-if="searchQuery"
      class="absolute z-10 top-1/2 -translate-y-1/2 right-12 cursor-pointer text-gray-400 hover:text-gray-600 transition"
      @click="reset"
    >
      <Icon name="ion:close-outline" size="18" />
    </span>
    <button
      type="submit"
      class="absolute z-10 right-3 top-1/2 -translate-y-1/2 transform transition"
      :class="{ 'cursor-pointer': searchQuery?.length >= 2, 'cursor-not-allowed': searchQuery?.length < 2 }"
    >
      <Icon 
        name="ph:arrow-right-bold" 
        size="20"
        :class="searchQuery?.length >= 2 ? 'text-red-600' : 'text-gray-300'" 
      />
    </button>
  </form>
</template>