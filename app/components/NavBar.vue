<template>
  <nav class="bg-gray-900 text-white shadow-md">
    <ul class="flex justify-center space-x-8 py-4">
      <li>
        <NuxtLink 
          to="/blog" 
          class="hover:text-yellow-400 transition-colors duration-300"
        >
          Blog
        </NuxtLink>
      </li>
      <li>
        <NuxtLink 
          to="/contact" 
          class="hover:text-yellow-400 transition-colors duration-300"
        >
          Contact
        </NuxtLink>
      </li>
      <li>
        <NuxtLink 
          to="/about" 
          class="hover:text-yellow-400 transition-colors duration-300"
        >
          About
        </NuxtLink>
      </li>
    </ul>
  </nav>
</template>
