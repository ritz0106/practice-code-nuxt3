<template>
  <div class="container mx-auto max-w-2xl">
    <header class="flex justify-between items-center mt-8">
      <div>
        <NuxtLink class="text-xl font-semibold p2 hover:text-blue-200">Ritz</NuxtLink>
      </div>
      <Menu />
    </header>
    <main class="p-2">
      <slot />
    </main>
  </div>
</template>