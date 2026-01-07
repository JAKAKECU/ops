<template>
  <div class="max-w-6xl mx-auto">
    <div class="bg-gradient-to-r from-green-500 to-emerald-600 rounded-xl p-8 text-white mb-8">
      <h1 class="text-3xl md:text-4xl font-bold mb-4">Welcome to Your Dashboard</h1>
      <p class="text-lg md:text-xl opacity-90 max-w-2xl">Track your metrics, manage your settings, and optimize your workflow in one place.</p>
    </div>
    
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 mb-8">
      <div class="bg-white rounded-lg border border-gray-200 p-6 shadow-sm">
        <div class="text-3xl font-bold text-gray-800 mb-2">24</div>
        <div class="text-gray-600">Projects</div>
      </div>
      <div class="bg-white rounded-lg border border-gray-200 p-6 shadow-sm">
        <div class="text-3xl font-bold text-gray-800 mb-2">142</div>
        <div class="text-gray-600">Tasks</div>
      </div>
      <div class="bg-white rounded-lg border border-gray-200 p-6 shadow-sm">
        <div class="text-3xl font-bold text-gray-800 mb-2">89%</div>
        <div class="text-gray-600">Completion</div>
      </div>
      <div class="bg-white rounded-lg border border-gray-200 p-6 shadow-sm">
        <div class="text-3xl font-bold text-gray-800 mb-2">32</div>
        <div class="text-gray-600">Team Members</div>
      </div>
    </div>
    
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-6">
      <div class="bg-white rounded-lg border border-gray-200 p-6">
        <h2 class="text-xl font-semibold text-gray-800 mb-4">Recent Activity</h2>
        <div class="space-y-4">
          <div class="flex items-start">
            <div class="flex-shrink-0 h-10 w-10 rounded-full bg-green-100 flex items-center justify-center mr-3">
              <span class="text-green-600">U</span>
            </div>
            <div>
              <h3 class="font-medium text-gray-800">Project Update</h3>
              <p class="text-sm text-gray-600">John Doe updated the project timeline</p>
              <p class="text-xs text-gray-500 mt-1">2 hours ago</p>
            </div>
          </div>
          <div class="flex items-start">
            <div class="flex-shrink-0 h-10 w-10 rounded-full bg-blue-100 flex items-center justify-center mr-3">
              <span class="text-blue-600">A</span>
            </div>
            <div>
              <h3 class="font-medium text-gray-800">New Task Assigned</h3>
              <p class="text-sm text-gray-600">You have been assigned a new task in Design System</p>
              <p class="text-xs text-gray-500 mt-1">4 hours ago</p>
            </div>
          </div>
          <div class="flex items-start">
            <div class="flex-shrink-0 h-10 w-10 rounded-full bg-purple-100 flex items-center justify-center mr-3">
              <span class="text-purple-600">S</span>
            </div>
            <div>
              <h3 class="font-medium text-gray-800">Meeting Reminder</h3>
              <p class="text-sm text-gray-600">Team sync scheduled for tomorrow at 10:00 AM</p>
              <p class="text-xs text-gray-500 mt-1">1 day ago</p>
            </div>
          </div>
        </div>
      </div>
      
      <div class="bg-white rounded-lg border border-gray-200 p-6">
        <h2 class="text-xl font-semibold text-gray-800 mb-4">Quick Actions</h2>
        <div class="grid grid-cols-2 gap-4">
          <button class="flex flex-col items-center justify-center p-4 border border-gray-200 rounded-lg hover:bg-gray-50 transition-colors">
            <div class="w-12 h-12 rounded-full bg-green-100 flex items-center justify-center mb-2">
              <svg class="w-6 h-6 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6v6m0 0v6m0-6h6m-6 0H6"></path>
              </svg>
            </div>
            <span class="text-sm font-medium text-gray-700">New Project</span>
          </button>
          <button class="flex flex-col items-center justify-center p-4 border border-gray-200 rounded-lg hover:bg-gray-50 transition-colors">
            <div class="w-12 h-12 rounded-full bg-blue-100 flex items-center justify-center mb-2">
              <svg class="w-6 h-6 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"></path>
              </svg>
            </div>
            <span class="text-sm font-medium text-gray-700">Add Team</span>
          </button>
          <button class="flex flex-col items-center justify-center p-4 border border-gray-200 rounded-lg hover:bg-gray-50 transition-colors">
            <div class="w-12 h-12 rounded-full bg-yellow-100 flex items-center justify-center mb-2">
              <svg class="w-6 h-6 text-yellow-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path>
              </svg>
            </div>
            <span class="text-sm font-medium text-gray-700">Documents</span>
          </button>
          <button class="flex flex-col items-center justify-center p-4 border border-gray-200 rounded-lg hover:bg-gray-50 transition-colors">
            <div class="w-12 h-12 rounded-full bg-red-100 flex items-center justify-center mb-2">
              <svg class="w-6 h-6 text-red-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path>
              </svg>
            </div>
            <span class="text-sm font-medium text-gray-700">Settings</span>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
useHead({
  title: 'Dashboard - Nuxt App',
  meta: [
    { name: 'description', content: 'Your application dashboard with metrics and activity' }
  ]
})

definePageMeta({
  // Add any required middleware here
})
</script>