<template>
  <div class="min-h-screen bg-gray-50 flex flex-col">
    <!-- Header -->
    <header class="bg-white border-b border-gray-200 py-4 px-6">
      <div class="max-w-7xl mx-auto flex justify-between items-center">
        <div class="flex items-center space-x-4">
          <h1 class="text-xl font-bold text-gray-800">Nuxt App</h1>
        </div>
        <nav>
          <ul class="flex space-x-6">
            <li>
              <NuxtLink to="/" class="text-gray-600 hover:text-green-600 transition-colors">
                Home
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="/example" class="text-gray-600 hover:text-green-600 transition-colors">
                Example
              </NuxtLink>
            </li>
          </ul>
        </nav>
      </div>
    </header>

    <!-- Main Layout with Sidebar and Content -->
    <div class="flex flex-1">
      <!-- Sidebar -->
      <aside class="w-64 bg-white border-r border-gray-200 py-6 px-4 hidden md:block">
        <nav>
          <ul class="space-y-2">
            <li>
              <NuxtLink to="/" class="block py-2 px-4 rounded-lg text-gray-700 hover:bg-gray-100 hover:text-green-600 transition-colors">
                Dashboard
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="/settings" class="block py-2 px-4 rounded-lg text-gray-700 hover:bg-gray-100 hover:text-green-600 transition-colors">
                Settings
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="/profile" class="block py-2 px-4 rounded-lg text-gray-700 hover:bg-gray-100 hover:text-green-600 transition-colors">
                Profile
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="/about" class="block py-2 px-4 rounded-lg text-gray-700 hover:bg-gray-100 hover:text-green-600 transition-colors">
                About
              </NuxtLink>
            </li>
          </ul>
        </nav>
      </aside>

      <!-- Main Content Area -->
      <main class="flex-1 py-6 px-4 md:px-6">
        <div class="max-w-7xl mx-auto">
          <NuxtPage />
        </div>
      </main>
    </div>

    <!-- Footer (not sticky as per user preferences) -->
    <footer class="bg-white border-t border-gray-200 py-6 px-6">
      <div class="max-w-7xl mx-auto text-center text-gray-600 text-sm">
        <p>© {{ new Date().getFullYear() }} Nuxt.js Application</p>
      </div>
    </footer>
  </div>
</template>

<script setup>
useHead({
  title: 'Nuxt App',
  meta: [
    { name: 'viewport', content: 'width=device-width, initial-scale=1' }
  ],
  link: [
    { rel: 'icon', href: '/favicon.ico' }
  ]
})
</script>