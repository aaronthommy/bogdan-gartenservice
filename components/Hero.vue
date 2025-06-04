<template>
  <section class="relative overflow-hidden bg-gradient-to-br from-green-50 to-green-100">
    <!-- Hauptinhalt -->
    <div class="container mx-auto px-4 py-16 lg:py-24">
      <div class="grid lg:grid-cols-2 gap-12 items-center">
        <!-- Text-Bereich -->
        <div class="space-y-8">
          <div class="space-y-4">
            <h1 class="text-4xl lg:text-6xl font-bold text-gray-900 leading-tight">
              Ihr Partner für
              <span class="text-green-600 block">Garten & Hausmeister</span>
              Service
            </h1>
            <p class="text-xl text-gray-600 leading-relaxed">
              Ob Privatgarten, Firmengelände oder Wohnanlage - wir sind für Sie immer da. 
              Mit uns haben Sie den richtigen Partner an Ihrer Seite!
            </p>
          </div>
          
          <!-- CTA Buttons -->
          <div class="flex flex-col sm:flex-row gap-4">
            <NuxtLink 
              to="/kontakt"
              class="bg-green-600 hover:bg-green-700 text-white px-8 py-4 rounded-lg font-semibold text-lg transition-all duration-300 transform hover:scale-105 text-center shadow-lg"
            >
              Kostenloses Angebot
            </NuxtLink>
            <NuxtLink 
              to="/leistungen"
              class="border-2 border-green-600 text-green-600 hover:bg-green-600 hover:text-white px-8 py-4 rounded-lg font-semibold text-lg transition-all duration-300 text-center"
            >
              Unsere Leistungen
            </NuxtLink>
          </div>

          <!-- Kontaktinfo -->
          <div class="flex items-center space-x-4 pt-4">
            <div class="bg-green-600 text-white p-3 rounded-full">
              <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
              </svg>
            </div>
            <div>
              <p class="text-sm text-gray-500">Rufen Sie uns an</p>
              <p class="text-lg font-semibold text-gray-900">0152 09613391</p>
            </div>
          </div>
        </div>

        <!-- Bild-Bereich -->
        <div class="relative">
          <div class="bg-white rounded-2xl shadow-2xl p-4 transform rotate-2 hover:rotate-0 transition-transform duration-300">
            <img 
              src="/img/baum-zugeschnitten-6x12.png" 
              alt="Professionell zugeschnittener Baum - Gartenservice Bogdan"
              class="w-full h-200 rounded-xl object-cover"
            >
          </div>
          <!-- Floating Logo -->
          <div class="absolute -top-4 -left-4 bg-white rounded-full p-4 shadow-xl">
            <img 
              src="/img/bogdan-garten-hausmeisterservice-logo-500x500.png" 
              alt="Bogdan Gartenservice Logo"
              class="w-16 h-16 object-contain"
            >
          </div>
        </div>
      </div>
    </div>

    <!-- Dekorative Elemente -->
    <div class="absolute top-0 right-0 w-64 h-64 bg-green-200 rounded-full -translate-y-32 translate-x-32 opacity-20"></div>
    <div class="absolute bottom-0 left-0 w-48 h-48 bg-green-300 rounded-full translate-y-24 -translate-x-24 opacity-20"></div>
  </section>
</template>

<script setup>
// Hero-Komponente für modernen Gartenservice-Auftritt
</script>