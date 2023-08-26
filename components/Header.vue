<template>
  <div class="flex justify-between bg-gray-700 px-10 py-6">
    <div class="flex space-x-2">
      <Icon class="h-10 w-10 text-green-600" name="fluent:chess-20-filled" />
      <h1 class="my-auto font-bold text-2xl text-green-600">
        Nizamani Chess Club
      </h1>
    </div>

    <div class="flex space-x-6">
      <NuxtLink to="/" class="my-auto cursor-pointer text-lg font-bold text-green-600"
        >Home</NuxtLink
      >
      <NuxtLink to="/rating" class="my-auto cursor-pointer text-lg font-bold text-green-600"
        >Rating</NuxtLink
      >
      <NuxtLink
        to="/about"
        class="my-auto cursor-pointer text-lg font-bold text-green-600"
        >About</NuxtLink
      >
      <NuxtLink to="/contact" class="my-auto cursor-pointer text-lg font-bold text-green-600"
        >Contact</NuxtLink
      >
    </div>
  </div>
</template>
