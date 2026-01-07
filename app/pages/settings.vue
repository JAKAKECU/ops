<template>
  <div>
    <h1 class="text-2xl font-bold text-gray-800 mb-6 text-center md:text-left">Settings</h1>
    
    <div class="space-y-6 max-w-3xl mx-auto">
      <!-- General Settings -->
      <section class="bg-white p-4 rounded-lg border border-gray-200">
        <h2 class="text-lg font-semibold text-gray-800 mb-4">General Settings</h2>
        <div class="space-y-4">
          <div class="flex flex-col sm:flex-row items-start sm:items-center justify-between gap-3 py-3 border-b border-gray-100">
            <div>
              <h3 class="font-medium text-gray-700">Dark Mode</h3>
              <p class="text-sm text-gray-500">Toggle dark/light theme</p>
            </div>
            <input type="checkbox" class="rounded border-gray-300 text-green-600 focus:ring-green-500" />
          </div>
          
          <div class="flex flex-col sm:flex-row items-start sm:items-center justify-between gap-3 py-3 border-b border-gray-100">
            <div>
              <h3 class="font-medium text-gray-700">Email Notifications</h3>
              <p class="text-sm text-gray-500">Receive email updates</p>
            </div>
            <input type="checkbox" checked class="rounded border-gray-300 text-green-600 focus:ring-green-500" />
          </div>
          
          <div class="flex flex-col sm:flex-row items-start sm:items-center justify-between gap-3 py-3 border-b border-gray-100">
            <div>
              <h3 class="font-medium text-gray-700">Push Notifications</h3>
              <p class="text-sm text-gray-500">Receive push notifications</p>
            </div>
            <input type="checkbox" checked class="rounded border-gray-300 text-green-600 focus:ring-green-500" />
          </div>
        </div>
      </section>
      
      <!-- Account Settings -->
      <section class="bg-white p-4 rounded-lg border border-gray-200">
        <h2 class="text-lg font-semibold text-gray-800 mb-4">Account Settings</h2>
        <div class="space-y-4">
          <div class="py-3 border-b border-gray-100">
            <h3 class="font-medium text-gray-700 mb-2">Change Password</h3>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
              <div>
                <label class="block text-sm font-medium text-gray-700 mb-1">Current Password</label>
                <input type="password" class="w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-green-500 focus:border-green-500" placeholder="Enter current password" />
              </div>
              <div>
                <label class="block text-sm font-medium text-gray-700 mb-1">New Password</label>
                <input type="password" class="w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-green-500 focus:border-green-500" placeholder="Enter new password" />
              </div>
            </div>
          </div>
          
          <div class="py-3 border-b border-gray-100">
            <h3 class="font-medium text-gray-700 mb-2">Email Address</h3>
            <div>
              <label class="block text-sm font-medium text-gray-700 mb-1">Email</label>
              <input type="email" class="w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-green-500 focus:border-green-500" placeholder="your.email@example.com" />
            </div>
          </div>
        </div>
      </section>
      
      <!-- Interface Settings -->
      <section class="bg-white p-4 rounded-lg border border-gray-200">
        <h2 class="text-lg font-semibold text-gray-800 mb-4">Interface Settings</h2>
        <div class="space-y-4">
          <div class="py-3 border-b border-gray-100">
            <h3 class="font-medium text-gray-700 mb-2">Language</h3>
            <select class="w-full md:w-64 px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-green-500 focus:border-green-500">
              <option>English</option>
              <option>Spanish</option>
              <option>French</option>
              <option>German</option>
            </select>
          </div>
          
          <div class="py-3 border-b border-gray-100">
            <h3 class="font-medium text-gray-700 mb-2">Timezone</h3>
            <select class="w-full md:w-64 px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-green-500 focus:border-green-500">
              <option>GMT+0</option>
              <option>GMT+1</option>
              <option>GMT+2</option>
              <option>GMT+7</option>
              <option>GMT+8</option>
            </select>
          </div>
        </div>
      </section>
      
      <!-- Action Buttons -->
      <div class="flex flex-col sm:flex-row justify-end space-y-2 sm:space-y-0 sm:space-x-3 pt-4">
        <button class="px-4 py-2 border border-gray-300 rounded-md text-gray-700 bg-white hover:bg-gray-50 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-green-500">
          Cancel
        </button>
        <button class="px-4 py-2 border border-transparent rounded-md shadow-sm text-white bg-green-600 hover:bg-green-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-green-500">
          Save Changes
        </button>
      </div>
    </div>
  </div>
</template>

<script setup>
useHead({
  title: 'Settings - Nuxt App',
  meta: [
    { name: 'description', content: 'Application settings page' }
  ]
})

definePageMeta({
  // Add any required middleware here
})
</script>