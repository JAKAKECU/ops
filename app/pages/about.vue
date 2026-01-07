<template>
  <div class="max-w-4xl mx-auto">
    <div class="bg-white rounded-lg border border-gray-200 p-8 mb-6">
      <h1 class="text-3xl font-bold text-gray-800 mb-4">About Our Application</h1>
      <p class="text-lg text-gray-600 mb-6">Learn more about our platform and what we do</p>
      
      <div class="prose prose-gray max-w-none">
        <h2 class="text-2xl font-semibold text-gray-800 mb-4">Our Mission</h2>
        <p class="mb-4 text-gray-600">
          We strive to create intuitive and powerful applications that help users achieve their goals efficiently. 
          Our platform combines cutting-edge technology with user-friendly design to provide the best experience possible.
        </p>
        
        <h2 class="text-2xl font-semibold text-gray-800 mb-4 mt-8">Features</h2>
        <ul class="list-disc pl-5 mb-6 space-y-2 text-gray-600">
          <li>Modern and responsive user interface</li>
          <li>Secure authentication and data protection</li>
          <li>Real-time updates and notifications</li>
          <li>Cross-platform compatibility</li>
          <li>Customizable settings and preferences</li>
          <li>Intuitive navigation and workflow</li>
        </ul>
        
        <h2 class="text-2xl font-semibold text-gray-800 mb-4 mt-8">Technology Stack</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mb-6">
          <div class="border border-gray-200 rounded-lg p-4">
            <h3 class="font-semibold text-gray-800 mb-2">Frontend</h3>
            <ul class="list-disc pl-5 text-gray-600 space-y-1">
              <li>Nuxt.js 4</li>
              <li>Tailwind CSS</li>
              <li>Vue.js 3</li>
            </ul>
          </div>
          <div class="border border-gray-200 rounded-lg p-4">
            <h3 class="font-semibold text-gray-800 mb-2">Development</h3>
            <ul class="list-disc pl-5 text-gray-600 space-y-1">
              <li>TypeScript</li>
              <li>ESLint</li>
              <li>Vite</li>
            </ul>
          </div>
        </div>
        
        <h2 class="text-2xl font-semibold text-gray-800 mb-4 mt-8">Contact Us</h2>
        <p class="mb-4 text-gray-600">
          Have questions or feedback? We'd love to hear from you. Reach out to our team for support or inquiries.
        </p>
        <div class="flex flex-wrap gap-4">
          <a href="mailto:info@example.com" class="inline-flex items-center px-4 py-2 border border-transparent rounded-md shadow-sm text-base font-medium text-white bg-green-600 hover:bg-green-700">
            Email Us
          </a>
          <a href="#" class="inline-flex items-center px-4 py-2 border border-gray-300 rounded-md shadow-sm text-base font-medium text-gray-700 bg-white hover:bg-gray-50">
            Support Center
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
useHead({
  title: 'About - Nuxt App',
  meta: [
    { name: 'description', content: 'Learn more about our application and company' }
  ]
})

definePageMeta({
  // Add any required middleware here
})
</script>