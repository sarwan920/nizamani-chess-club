<script setup>
const { data: ishaque } = await useFetch(
  "https://api.chess.com/pub/player/muhammadnizamani"
);
const { data: sarwan } = await useFetch(
  "https://api.chess.com/pub/player/sarwan920"
);
</script>

<template>
  <div class="container px-10 h-screen">
    <h1 class="text-center text-4xl font-bold my-10 text-green-600">
      Welcome to Nizamani Chess Club
    </h1>
    <div class="grid grid-cols-4 gap-4">
      <div class="shadow-xl space-y-3 rounded-2xl border border-green-600 p-4">
        <img
          class="mx-auto rounded-full h-24"
          :src="ishaque.avatar"
          alt="ishaque"
        />
        <h2 class="text-center text-lg font-bold text-green-600">
          {{ ishaque.name }}
        </h2>
      </div>

      <div class="shadow-xl space-y-3 rounded-2xl border border-green-600 p-4">
        <img
          class="mx-auto rounded-full h-24"
          :src="sarwan.avatar"
          alt="ishaque"
        />
        <h2 class="text-center text-lg font-bold text-green-600">
          {{ sarwan.name }}
        </h2>
      </div>
    </div>
  </div>
</template>
