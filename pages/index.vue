<template>
  <div class="min-h-screen flex justify-center items-center space-x-4">
    <nuxt-link
      to="/test"
      class="
        bg-indigo-100
        text-indigo-600
        px-4
        py-2
        max-w-md
        rounded-lg
        text-center
      "
    >
      Test Page
    </nuxt-link>

    <a class="
      bg-red-100
        text-red-600
        px-4
        py-2
        max-w-md
        rounded-lg
        text-center" 
        href="/api/hello">
        Api (Hello)
    </a>
  </div>
</template>