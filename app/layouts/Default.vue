<template>
  <div class="flex h-screen">
    <!-- Sidebar (Left 1/3) -->
    <aside class="w-1/3 bg-white p-6 border-r">
      <div class="text-2xl font-bold mb-6">My Site</div>
      <nav class="space-y-4">
        <NuxtLink to="/" class="block text-lg hover:text-gray-600"
          >Home</NuxtLink
        >
        <NuxtLink to="/portfolio" class="block text-lg hover:text-gray-600"
          >Portfolio</NuxtLink
        >
        <NuxtLink to="/projects" class="block text-lg hover:text-gray-600"
          >Projects</NuxtLink
        >
        <NuxtLink to="/about" class="block text-lg hover:text-gray-600"
          >About</NuxtLink
        >
      </nav>
    </aside>

    <!-- Main Content (Right 2/3) -->
    <main class="w-2/3 p-10">
      <slot />
      <!-- This loads Nuxt Content pages -->
    </main>
  </div>
</template>
