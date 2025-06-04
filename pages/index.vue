<template>
  <div>
    <!-- Hero-Bereich -->
    <Hero />

    <!-- Services Overview -->
    <section class="py-16 bg-white">
      <div class="container mx-auto px-4">
        <div class="text-center mb-12">
          <h2 class="text-3xl lg:text-4xl font-bold text-gray-900 mb-4">
            Unsere Hauptleistungen
          </h2>
          <p class="text-xl text-gray-600 max-w-3xl mx-auto">
            Vom einmaligen Rasenschnitt bis zur Dauerpflege Ihrer gesamten Anlage
          </p>
        </div>

        <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
          <div class="text-center group">
            <div class="bg-green-50 rounded-full w-20 h-20 mx-auto mb-4 flex items-center justify-center group-hover:bg-green-100 transition-colors duration-300">
              <svg class="w-10 h-10 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
              </svg>
            </div>
            <h3 class="text-lg font-semibold text-gray-900 mb-2">Rasenpflege</h3>
            <p class="text-gray-600 text-sm">Vertikutieren, lüften, mähen</p>
          </div>

          <div class="text-center group">
            <div class="bg-green-50 rounded-full w-20 h-20 mx-auto mb-4 flex items-center justify-center group-hover:bg-green-100 transition-colors duration-300">
              <svg class="w-10 h-10 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"/>
              </svg>
            </div>
            <h3 class="text-lg font-semibold text-gray-900 mb-2">Heckenschnitt</h3>
            <p class="text-gray-600 text-sm">Professioneller Formschnitt</p>
          </div>

          <div class="text-center group">
            <div class="bg-green-50 rounded-full w-20 h-20 mx-auto mb-4 flex items-center justify-center group-hover:bg-green-100 transition-colors duration-300">
              <svg class="w-10 h-10 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 7l-.867 12.142A2 2 0 0116.138 21H7.862a2 2 0 01-1.995-1.858L5 7m5 4v6m4-6v6m1-10V4a1 1 0 00-1-1h-4a1 1 0 00-1 1v3M4 7h16"/>
              </svg>
            </div>
            <h3 class="text-lg font-semibold text-gray-900 mb-2">Reinigung</h3>
            <p class="text-gray-600 text-sm">Terrassen & Gehwege</p>
          </div>

          <div class="text-center group">
            <div class="bg-green-50 rounded-full w-20 h-20 mx-auto mb-4 flex items-center justify-center group-hover:bg-green-100 transition-colors duration-300">
              <svg class="w-10 h-10 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11.049 2.927c.3-.921 1.603-.921 1.902 0l1.519 4.674a1 1 0 00.95.69h4.915c.969 0 1.371 1.24.588 1.81l-3.976 2.888a1 1 0 00-.363 1.118l1.518 4.674c.3.922-.755 1.688-1.538 1.118l-3.976-2.888a1 1 0 00-1.176 0l-3.976 2.888c-.783.57-1.838-.197-1.538-1.118l1.518-4.674a1 1 0 00-.363-1.118l-3.976-2.888c-.784-.57-.38-1.81.588-1.81h4.914a1 1 0 00.951-.69l1.519-4.674z"/>
              </svg>
            </div>
            <h3 class="text-lg font-semibold text-gray-900 mb-2">Baumpflege</h3>
            <p class="text-gray-600 text-sm">Fällung & Beschnitt</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Bildergalerie mit Vorher/Nachher -->
    <section class="py-16 bg-gray-50">
      <div class="container mx-auto px-4">
        <div class="text-center mb-12">
          <h2 class="text-3xl lg:text-4xl font-bold text-gray-900 mb-4">
            Unsere Arbeit spricht für sich
          </h2>
          <p class="text-xl text-gray-600">
            Sehen Sie selbst, wie wir Ihren Garten verwandeln können
          </p>
        </div>

        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
          <!-- Vorher/Nachher Hütte -->
          <div class="bg-white rounded-xl shadow-lg overflow-hidden hover:shadow-xl transition-shadow duration-300">
            <div class="relative">
              <img 
                src="/img/vorher-nachher-huette-im-garten-neu.png" 
                alt="Vorher/Nachher: Gartenweg zur Hütte - Professionelle Steinverlegung"
                class="w-full h-64 object-cover"
              >
              <div class="absolute top-4 left-4 bg-green-600 text-white px-3 py-1 rounded-full text-sm font-medium">
                Vorher/Nachher
              </div>
            </div>
            <div class="p-6">
              <h3 class="text-xl font-semibold text-gray-900 mb-2">Gartenweg Neugestaltung</h3>
              <p class="text-gray-600">Neue Steinplatten verlegt und Unkraut professionell entfernt</p>
            </div>
          </div>

          <!-- Vorher/Nachher Pflanzen -->
          <div class="bg-white rounded-xl shadow-lg overflow-hidden hover:shadow-xl transition-shadow duration-300">
            <div class="relative">
              <img 
                src="/img/vorher-nachher-pflanzen-garten.png" 
                alt="Vorher/Nachher: Pflanzenpflege - Bodenvorbereitung und Gartengestaltung"
                class="w-full h-64 object-cover"
              >
              <div class="absolute top-4 left-4 bg-green-600 text-white px-3 py-1 rounded-full text-sm font-medium">
                Vorher/Nachher
              </div>
            </div>
            <div class="p-6">
              <h3 class="text-xl font-semibold text-gray-900 mb-2">Pflanzenpflege</h3>
              <p class="text-gray-600">Neue Bodenvorbereitung für gesunde Pflanzen</p>
            </div>
          </div>

          <!-- Efeu Entfernung -->
          <div class="bg-white rounded-xl shadow-lg overflow-hidden hover:shadow-xl transition-shadow duration-300">
            <div class="relative">
              <img 
                src="/img/efeu-von-wand-entfernen-6x12.png" 
                alt="Efeu-Entfernung von Hauswand - Fassadenreinigung"
                class="w-full h-64 object-cover"
              >
              <div class="absolute top-4 left-4 bg-blue-600 text-white px-3 py-1 rounded-full text-sm font-medium">
                Spezialservice
              </div>
            </div>
            <div class="p-6">
              <h3 class="text-xl font-semibold text-gray-900 mb-2">Efeu-Entfernung</h3>
              <p class="text-gray-600">Schonende Entfernung von Efeu und anderen Kletterpflanzen</p>
            </div>
          </div>

          <!-- Eingepflanzter Weg -->
          <div class="bg-white rounded-xl shadow-lg overflow-hidden hover:shadow-xl transition-shadow duration-300">
            <div class="relative">
              <img 
                src="/img/eingepflanzt-weg-6x12.png" 
                alt="Professionelle Bepflanzung entlang Steinweg"
                class="w-full h-64 object-cover"
              >
            </div>
            <div class="p-6">
              <h3 class="text-xl font-semibold text-gray-900 mb-2">Beetgestaltung</h3>
              <p class="text-gray-600">Professionelle Bepflanzung entlang von Gehwegen</p>
            </div>
          </div>

          <!-- Reinigung Haustür -->
          <div class="bg-white rounded-xl shadow-lg overflow-hidden hover:shadow-xl transition-shadow duration-300">
            <div class="relative">
              <img 
                src="/img/reinigung-haustuer.png" 
                alt="Professionelle Reinigung von Eingangsbereichen"
                class="w-full h-64 object-cover"
              >
            </div>
            <div class="p-6">
              <h3 class="text-xl font-semibold text-gray-900 mb-2">Eingangsreinigung</h3>
              <p class="text-gray-600">Saubere und einladende Eingangsbereiche</p>
            </div>
          </div>

          <!-- Gartengeräte -->
          <div class="bg-white rounded-xl shadow-lg overflow-hidden hover:shadow-xl transition-shadow duration-300">
            <div class="relative">
              <img 
                src="/img/gartengeraete.png" 
                alt="Professionelle Gartengeräte - Rasenmäher, Trimmer, Laubbläser"
                class="w-full h-64 object-cover"
              >
              <div class="absolute top-4 left-4 bg-yellow-600 text-white px-3 py-1 rounded-full text-sm font-medium">
                Profi-Ausrüstung
              </div>
            </div>
            <div class="p-6">
              <h3 class="text-xl font-semibold text-gray-900 mb-2">Professionelle Geräte</h3>
              <p class="text-gray-600">Hochwertige Ausrüstung für beste Ergebnisse</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Warum uns wählen -->
    <section class="py-16 bg-white">
      <div class="container mx-auto px-4">
        <div class="grid lg:grid-cols-2 gap-12 items-center">
          <div>
            <h2 class="text-3xl lg:text-4xl font-bold text-gray-900 mb-6">
              Warum Bogdan Gartenservice?
            </h2>
            <div class="space-y-6">
              <div class="flex items-start space-x-4">
                <div class="bg-green-100 rounded-full p-3 flex-shrink-0">
                  <svg class="w-6 h-6 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
                  </svg>
                </div>
                <div>
                  <h3 class="text-xl font-semibold text-gray-900 mb-2">Zuverlässig & Pünktlich</h3>
                  <p class="text-gray-600">Termine werden eingehalten - darauf können Sie sich verlassen</p>
                </div>
              </div>

              <div class="flex items-start space-x-4">
                <div class="bg-green-100 rounded-full p-3 flex-shrink-0">
                  <svg class="w-6 h-6 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"/>
                  </svg>
                </div>
                <div>
                  <h3 class="text-xl font-semibold text-gray-900 mb-2">Faire Preise</h3>
                  <p class="text-gray-600">Transparente Kostenvoranschläge ohne versteckte Kosten</p>
                </div>
              </div>

              <div class="flex items-start space-x-4">
                <div class="bg-green-100 rounded-full p-3 flex-shrink-0">
                  <svg class="w-6 h-6 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11.049 2.927c.3-.921 1.603-.921 1.902 0l1.519 4.674a1 1 0 00.95.69h4.915c.969 0 1.371 1.24.588 1.81l-3.976 2.888a1 1 0 00-.363 1.118l1.518 4.674c.3.922-.755 1.688-1.538 1.118l-3.976-2.888a1 1 0 00-1.176 0l-3.976 2.888c-.783.57-1.838-.197-1.538-1.118l1.518-4.674a1 1 0 00-.363-1.118l-3.976-2.888c-.784-.57-.38-1.81.588-1.81h4.914a1 1 0 00.951-.69l1.519-4.674z"/>
                  </svg>
                </div>
                <div>
                  <h3 class="text-xl font-semibold text-gray-900 mb-2">Erfahrung & Qualität</h3>
                  <p class="text-gray-600">Jahrelange Erfahrung für professionelle Ergebnisse</p>
                </div>
              </div>
            </div>

            <div class="mt-8">
              <NuxtLink 
                to="/kontakt"
                class="bg-green-600 hover:bg-green-700 text-white px-8 py-4 rounded-lg font-semibold text-lg transition-all duration-300 inline-block"
              >
                Jetzt kostenlos anfragen
              </NuxtLink>
            </div>
          </div>

          <div class="relative">
            <div class="bg-green-50 rounded-2xl p-8 transform hover:scale-105 transition-transform duration-300">
              <div class="text-center">
                <div class="bg-white rounded-full p-6 w-32 h-32 mx-auto mb-6 shadow-lg">
                  <img 
                    src="/img/bogdan-garten-hausmeisterservice-logo-500x500.png" 
                    alt="Bogdan Gartenservice Logo"
                    class="w-full h-full object-contain"
                  >
                </div>
                <h3 class="text-2xl font-bold text-gray-900 mb-4">Kostenlose Beratung</h3>
                <p class="text-gray-600 mb-6">
                  Rufen Sie uns an und lassen Sie sich unverbindlich beraten
                </p>
                <a 
                  href="tel:015209613391"
                  class="text-3xl font-bold text-green-600 hover:text-green-700 transition-colors duration-200"
                >
                  0152 09613391
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>
import Hero from '~/components/Hero.vue'
</script>