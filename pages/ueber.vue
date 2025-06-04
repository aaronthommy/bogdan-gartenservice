<template>
  <div class="py-12">
    <!-- Header -->
    <section class="text-center mb-16">
      <h1 class="text-4xl lg:text-5xl font-bold text-gray-900 mb-6">
        Über uns
      </h1>
      <p class="text-xl text-gray-600 max-w-3xl mx-auto">
        Lernen Sie Bogdan Gartenservice kennen - Ihren zuverlässigen Partner für alle Garten- und Hausmeisterarbeiten
      </p>
    </section>

    <!-- Hauptinhalt -->
    <div class="grid lg:grid-cols-2 gap-12 items-center mb-16">
      <!-- Text -->
      <div class="space-y-6">
        <div>
          <h2 class="text-3xl font-bold text-gray-900 mb-4">
            Willkommen bei Bogdan Gartenservice
          </h2>
          <p class="text-lg text-gray-600 leading-relaxed">
            Seit Jahren sind wir Ihr zuverlässiger Partner für professionelle Garten- und Hausmeisterservices. 
            Ob Privatgarten, Firmengelände oder Wohnanlage - wir sind für Sie immer da.
          </p>
        </div>

        <div>
          <h3 class="text-2xl font-semibold text-gray-900 mb-3">Unsere Mission</h3>
          <p class="text-gray-600 leading-relaxed">
            Unser Ziel ist es, individuelle Gartenkonzepte zu entwickeln, die perfekt zu Ihren
            Bedürfnissen passen – sei es ein gepflegter Rasen, eine blühende Gartenanlage oder eine 
            saubere Terrassenlandschaft. Mit uns haben Sie den richtigen Partner an Ihrer Seite!
          </p>
        </div>

        <div>
          <h3 class="text-2xl font-semibold text-gray-900 mb-3">Was uns auszeichnet</h3>
          <div class="space-y-3">
            <div class="flex items-center space-x-3">
              <svg class="w-5 h-5 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
              </svg>
              <span class="text-gray-700">Jahrelange Erfahrung in der Gartenpflege</span>
            </div>
            <div class="flex items-center space-x-3">
              <svg class="w-5 h-5 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
              </svg>
              <span class="text-gray-700">Zuverlässige und pünktliche Arbeitsweise</span>
            </div>
            <div class="flex items-center space-x-3">
              <svg class="w-5 h-5 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
              </svg>
              <span class="text-gray-700">Faire und transparente Preisgestaltung</span>
            </div>
            <div class="flex items-center space-x-3">
              <svg class="w-5 h-5 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
              </svg>
              <span class="text-gray-700">Professionelle Ausrüstung und Werkzeuge</span>
            </div>
          </div>
        </div>
      </div>

      <!-- Bild -->
      <div class="relative">
        <div class="bg-green-50 rounded-2xl p-8 transform hover:scale-105 transition-transform duration-300">
          <img 
            src="/img/baum-zugeschnitten-6x12.png" 
            alt="Professionell zugeschnittener Baum - Beispiel unserer Arbeit"
            class="w-full h-150 rounded-xl object-cover shadow-lg"
          >
        </div>
        <!-- Logo Overlay -->
        <div class="absolute -bottom-4 -right-4 bg-white rounded-full p-4 shadow-xl">
          <img 
            src="/img/bogdan-garten-hausmeisterservice-logo-500x500.png" 
            alt="Bogdan Gartenservice Logo"
            class="w-16 h-16 object-contain"
          >
        </div>
      </div>
    </div>

    <!-- Service-Spektrum -->
    <section class="bg-gray-50 rounded-2xl p-8 mb-16">
      <h2 class="text-3xl font-bold text-gray-900 text-center mb-8">
        Unser Service-Spektrum
      </h2>
      <p class="text-lg text-gray-600 text-center mb-12 max-w-3xl mx-auto">
        Egal, ob einmaliger Rasenschnitt oder die Dauerpflege Ihrer gesamten Anlage - 
        wir bieten Ihnen ein umfassendes Leistungsspektrum.
      </p>

      <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
        <div class="text-center bg-white rounded-xl p-6 shadow-sm hover:shadow-lg transition-shadow duration-300">
          <div class="bg-green-100 rounded-full w-16 h-16 mx-auto mb-4 flex items-center justify-center">
            <svg class="w-8 h-8 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
            </svg>
          </div>
          <h3 class="text-lg font-semibold text-gray-900 mb-2">Privatgärten</h3>
          <p class="text-gray-600 text-sm">Individuelle Betreuung Ihres privaten Gartenparadieses</p>
        </div>

        <div class="text-center bg-white rounded-xl p-6 shadow-sm hover:shadow-lg transition-shadow duration-300">
          <div class="bg-blue-100 rounded-full w-16 h-16 mx-auto mb-4 flex items-center justify-center">
            <svg class="w-8 h-8 text-blue-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"/>
            </svg>
          </div>
          <h3 class="text-lg font-semibold text-gray-900 mb-2">Firmengelände</h3>
          <p class="text-gray-600 text-sm">Professionelle Außenanlagenpflege für Unternehmen</p>
        </div>

        <div class="text-center bg-white rounded-xl p-6 shadow-sm hover:shadow-lg transition-shadow duration-300">
          <div class="bg-purple-100 rounded-full w-16 h-16 mx-auto mb-4 flex items-center justify-center">
            <svg class="w-8 h-8 text-purple-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"/>
            </svg>
          </div>
          <h3 class="text-lg font-semibold text-gray-900 mb-2">Wohnanlagen</h3>
          <p class="text-gray-600 text-sm">Gemeinschaftsflächen und Außenanlagen von Wohnanlagen</p>
        </div>

        <div class="text-center bg-white rounded-xl p-6 shadow-sm hover:shadow-lg transition-shadow duration-300">
          <div class="bg-yellow-100 rounded-full w-16 h-16 mx-auto mb-4 flex items-center justify-center">
            <svg class="w-8 h-8 text-yellow-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/>
            </svg>
          </div>
          <h3 class="text-lg font-semibold text-gray-900 mb-2">Notfall-Service</h3>
          <p class="text-gray-600 text-sm">Schnelle Hilfe bei Sturmschäden und anderen Notfällen</p>
        </div>
      </div>
    </section>

    <!-- Arbeitsweise -->
    <section class="mb-16">
      <div class="text-center mb-12">
        <h2 class="text-3xl font-bold text-gray-900 mb-4">
          So arbeiten wir
        </h2>
        <p class="text-xl text-gray-600">
          Von der ersten Beratung bis zur regelmäßigen Pflege
        </p>
      </div>

      <div class="grid md:grid-cols-3 gap-8">
        <!-- Schritt 1 -->
        <div class="text-center relative">
          <div class="bg-green-600 text-white rounded-full w-16 h-16 mx-auto mb-6 flex items-center justify-center text-2xl font-bold">
            1
          </div>
          <h3 class="text-xl font-semibold text-gray-900 mb-4">Kostenlose Beratung</h3>
          <p class="text-gray-600 leading-relaxed">
            Wir besichtigen Ihr Gelände, besprechen Ihre Wünsche und erstellen Ihnen 
            ein kostenloses und unverbindliches Angebot.
          </p>
          <!-- Verbindungslinie -->
          <div class="hidden md:block absolute top-8 left-full w-full h-0.5 bg-gray-300 transform -translate-x-1/2"></div>
        </div>

        <!-- Schritt 2 -->
        <div class="text-center relative">
          <div class="bg-green-600 text-white rounded-full w-16 h-16 mx-auto mb-6 flex items-center justify-center text-2xl font-bold">
            2
          </div>
          <h3 class="text-xl font-semibold text-gray-900 mb-4">Terminplanung</h3>
          <p class="text-gray-600 leading-relaxed">
            Nach Ihrer Zusage vereinbaren wir gemeinsam passende Termine, 
            die sich nach Ihren Bedürfnissen und den saisonalen Gegebenheiten richten.
          </p>
          <!-- Verbindungslinie -->
          <div class="hidden md:block absolute top-8 left-full w-full h-0.5 bg-gray-300 transform -translate-x-1/2"></div>
        </div>

        <!-- Schritt 3 -->
        <div class="text-center">
          <div class="bg-green-600 text-white rounded-full w-16 h-16 mx-auto mb-6 flex items-center justify-center text-2xl font-bold">
            3
          </div>
          <h3 class="text-xl font-semibold text-gray-900 mb-4">Professionelle Ausführung</h3>
          <p class="text-gray-600 leading-relaxed">
            Wir führen alle Arbeiten zuverlässig, pünktlich und mit professioneller 
            Ausrüstung durch - für beste Ergebnisse.
          </p>
        </div>
      </div>
    </section>

    <!-- Kontakt CTA -->
    <section class="bg-green-600 rounded-2xl p-8 text-center text-white">
      <h2 class="text-3xl font-bold mb-4">Lernen Sie uns kennen!</h2>
      <p class="text-xl mb-8 opacity-90">
        Lassen Sie uns gemeinsam Ihren Traumgarten verwirklichen
      </p>
      <div class="flex flex-col sm:flex-row gap-4 justify-center">
        <NuxtLink 
          to="/kontakt"
          class="bg-white text-green-600 hover:bg-gray-100 px-8 py-4 rounded-lg font-semibold text-lg transition-colors duration-300"
        >
          Kontakt aufnehmen
        </NuxtLink>
        <a 
          href="tel:015209613391"
          class="border-2 border-white text-white hover:bg-white hover:text-green-600 px-8 py-4 rounded-lg font-semibold text-lg transition-colors duration-300"
        >
          0152 09613391
        </a>
      </div>
    </section>
  </div>
</template>

<script setup>
// Über uns Seite mit detaillierten Informationen über den Service
</script>