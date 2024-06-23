<template>
    <header class="bg-gray-100 py-4 w-full fixed top-0">
      <nav class="container mx-auto p-4 flex justify-between md:flex">
        <div class="flex items-center">
          <img src="../assets/logo.png" alt="Logo" class="h-8 w-8 mr-2">
          <span class="text-lg font-bold">Logo</span>
        </div>
        <button class="md:hidden" aria-label="Toggle navigation">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
          </svg>
        </button>
        <ul class="hidden md:flex flex-wrap justify-end">
          <li class="mr-6"><a href="#features" class="text-gray-600 hover:text-gray-900">Features</a></li>
          <li><a href="#contact" class="text-gray-600 hover:text-gray-900">Contact</a></li>
        </ul>
      </nav>
    </header>
  </template>
  
  <script>
  export default {
    name: 'HeaderSection',
  }
  </script>
  
  <style scoped>
  /* Add any additional styles here */
  </style>