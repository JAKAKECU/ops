<template>
  <div class="min-h-screen bg-gray-50">
    <!-- Header -->
    <header class="bg-white border-b border-gray-200 py-4 px-4">
      <div class="max-w-6xl mx-auto flex justify-between items-center">
        <h1 class="text-xl font-bold text-gray-800">Nuxt + Tailwind Example</h1>
        <nav>
          <ul class="flex space-x-4">
            <li><NuxtLink to="/" class="text-gray-600 hover:text-green-600 transition-colors">Home</NuxtLink></li>
            <li><NuxtLink to="/example" class="text-green-600 font-medium">Example</NuxtLink></li>
          </ul>
        </nav>
      </div>
    </header>

    <!-- Main Content - Centered as per user preferences -->
    <main class="py-8 px-4">
      <div class="max-w-4xl mx-auto text-center">
        <h2 class="text-2xl md:text-3xl font-bold text-gray-800 mb-6">Welcome to Nuxt.js with Tailwind CSS</h2>
        
        <div class="grid grid-cols-1 md:grid-cols-3 gap-4 mb-8">
          <div class="bg-white p-4 rounded-lg border border-gray-200">
            <h3 class="text-lg font-semibold mb-2 text-gray-800">Nuxt.js</h3>
            <p class="text-gray-600 text-sm">The Intuitive Vue Framework</p>
          </div>
          
          <div class="bg-white p-4 rounded-lg border border-gray-200">
            <h3 class="text-lg font-semibold mb-2 text-gray-800">Tailwind CSS</h3>
            <p class="text-gray-600 text-sm">Utility-First CSS Framework</p>
          </div>
          
          <div class="bg-white p-4 rounded-lg border border-gray-200">
            <h3 class="text-lg font-semibold mb-2 text-gray-800">Nuxt UI</h3>
            <p class="text-gray-600 text-sm">Beautiful Component Library</p>
          </div>
        </div>

        <div class="bg-white p-6 rounded-lg border border-gray-200 text-left max-w-2xl mx-auto">
          <h3 class="text-lg font-semibold mb-4 text-gray-800">Features:</h3>
          <ul class="space-y-2 text-gray-600">
            <li class="flex items-start">
              <span class="text-green-500 mr-2">✓</span>
              <span>Server-Side Rendering (SSR) and Static Site Generation (SSG)</span>
            </li>
            <li class="flex items-start">
              <span class="text-green-500 mr-2">✓</span>
              <span>Automatic code splitting</span>
            </li>
            <li class="flex items-start">
              <span class="text-green-500 mr-2">✓</span>
              <span>Hot Module Replacement (HMR) for fast development</span>
            </li>
            <li class="flex items-start">
              <span class="text-green-500 mr-2">✓</span>
              <span>TypeScript support</span>
            </li>
            <li class="flex items-start">
              <span class="text-green-500 mr-2">✓</span>
              <span>Responsive design with Tailwind CSS</span>
            </li>
          </ul>
        </div>
      </div>
    </main>

    <!-- Footer (not sticky as per user preferences) -->
    <footer class="bg-gray-100 border-t border-gray-200 py-4 px-4">
      <div class="max-w-6xl mx-auto text-center text-gray-600 text-sm">
        <p>© {{ new Date().getFullYear() }} Nuxt.js + Tailwind CSS Example</p>
      </div>
    </footer>
  </div>
</template>

<script setup>
useHead({
  title: 'Nuxt + Tailwind Example',
  meta: [
    { name: 'description', content: 'Example page showing Nuxt.js with Tailwind CSS integration' }
  ]
})
</script>