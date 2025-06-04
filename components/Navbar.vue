<template>
  <nav class="bg-green-600 text-white">
    <div class="container mx-auto px-4 py-3 flex justify-between items-center">
      <div class="text-xl font-bold">
        <NuxtLink to="/">Gartenservice</NuxtLink>
      </div>
      <ul class="flex space-x-6">
        <li>
          <NuxtLink
            to="/"
            class="hover:text-green-200"
            active-class="underline"
            exact
          >Home</NuxtLink>
        </li>
        <li>
          <NuxtLink
            to="/ueber"
            class="hover:text-green-200"
            active-class="underline"
          >Über uns</NuxtLink>
        </li>
        <li>
          <NuxtLink
            to="/leistungen"
            class="hover:text-green-200"
            active-class="underline"
          >Leistungen</NuxtLink>
        </li>
        <li>
          <NuxtLink
            to="/kontakt"
            class="hover:text-green-200"
            active-class="underline"
          >Kontakt</NuxtLink>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script setup>
// keine Logik nötig, nur statische Links
</script>
