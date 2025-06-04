<template>
  <div>
    <!-- Hero Section -->
    <section class="relative bg-gradient-to-r from-green-600 to-green-700 text-white py-12">
      <div class="container mx-auto px-4 text-center">
        <h1 class="text-4xl md:text-5xl font-bold mb-4">
          Unsere Leistungen
        </h1>
        <p class="text-lg text-green-100 max-w-2xl mx-auto">
          Professionelle Gartenpflege für Privatgärten, Firmengelände und Wohnanlagen. 
          Von der einmaligen Pflege bis zur dauerhaften Betreuung.
        </p>
      </div>
    </section>

    <!-- Hauptleistungen -->
    <section class="py-16">
      <div class="container mx-auto px-4 max-w-7xl">
        
        <!-- Gartenpflege & Rasenpflege -->
        <div class="flex flex-col lg:flex-row gap-8 lg:gap-12 items-center mb-16">
          <div class="flex-1">
            <h2 class="text-3xl font-bold text-gray-800 mb-4">Gartenpflege & Rasenpflege</h2>
            <p class="text-gray-600 mb-6">
              Professionelle Pflege für einen perfekten Garten. Wir sorgen dafür, 
              dass Ihr Rasen gesund und grün bleibt und Ihre Beete immer gepflegt aussehen.
            </p>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
              <div class="bg-white p-4 rounded-lg border shadow-sm">
                <h4 class="font-semibold text-gray-800 mb-2">Rasenpflege</h4>
                <ul class="text-sm text-gray-600 space-y-1">
                  <li>• Regelmäßiges Mähen</li>
                  <li>• Vertikutieren & Belüften</li>
                  <li>• Düngung & Nachsaat</li>
                </ul>
              </div>
              <div class="bg-white p-4 rounded-lg border shadow-sm">
                <h4 class="font-semibold text-gray-800 mb-2">Beetpflege</h4>
                <ul class="text-sm text-gray-600 space-y-1">
                  <li>• Unkrautentfernung</li>
                  <li>• Bepflanzung & Gestaltung</li>
                  <li>• Bodenpflege & Mulchen</li>
                </ul>
              </div>
            </div>
          </div>
          <div class="flex-1 lg:max-w-md">
            <img 
              src="/img/gartengeraete.png" 
              alt="Professionelle Gartengeräte für die Rasenpflege" 
              class="w-full h-auto rounded-xl shadow-lg"
            />
          </div>
        </div>

        <!-- Baumpflege -->
        <div class="flex flex-col lg:flex-row-reverse gap-8 lg:gap-12 items-center mb-16">
          <div class="flex-1">
            <h2 class="text-3xl font-bold text-gray-800 mb-4">Baumpflege & Baumfällung</h2>
            <p class="text-gray-600 mb-6">
              Fachgerechte Baumpflege für gesunde und sichere Bäume. 
              Von der Kronenauslichtung bis zur kompletten Baumfällung.
            </p>
            <div class="space-y-4">
              <div class="flex items-start gap-3">
                <div class="w-2 h-2 bg-green-600 rounded-full mt-3 flex-shrink-0"></div>
                <div>
                  <h4 class="font-semibold text-gray-800">Professioneller Baumschnitt</h4>
                  <p class="text-gray-600 text-sm">Kronenauslichtung und fachgerechter Rückschnitt</p>
                </div>
              </div>
              <div class="flex items-start gap-3">
                <div class="w-2 h-2 bg-green-600 rounded-full mt-3 flex-shrink-0"></div>
                <div>
                  <h4 class="font-semibold text-gray-800">Sichere Baumfällung</h4>
                  <p class="text-gray-600 text-sm">Komplette Entfernung mit professioneller Ausrüstung</p>
                </div>
              </div>
              <div class="flex items-start gap-3">
                <div class="w-2 h-2 bg-green-600 rounded-full mt-3 flex-shrink-0"></div>
                <div>
                  <h4 class="font-semibold text-gray-800">Entsorgung inklusive</h4>
                  <p class="text-gray-600 text-sm">Komplette Entsorgung des Grünschnitts</p>
                </div>
              </div>
            </div>
          </div>
          <div class="flex-1 lg:max-w-sm">
            <img 
              src="/img/baum-zugeschnitten-6x12.png" 
              alt="Professionell zugeschnittener Baum" 
              class="w-full h-auto rounded-xl shadow-lg"
            />
          </div>
        </div>

        <!-- Spezielle Reinigungsarbeiten -->
        <div class="flex flex-col lg:flex-row gap-8 lg:gap-12 items-center mb-16">
          <div class="flex-1">
            <h2 class="text-3xl font-bold text-gray-800 mb-4">Spezielle Reinigungsarbeiten</h2>
            <p class="text-gray-600 mb-6">
              Professionelle Reinigung für Terrassen, Gehwege und Fassaden. 
              Auch hartnäckige Verschmutzungen und Bewuchs entfernen wir zuverlässig.
            </p>
            <div class="grid grid-cols-1 gap-3">
              <div class="bg-green-50 p-4 rounded-lg">
                <h4 class="font-semibold text-gray-800 mb-1">✓ Efeu-Entfernung von Hauswänden</h4>
                <p class="text-gray-600 text-sm">Schonende Beseitigung von Wandbewuchs ohne Fassadenschäden</p>
              </div>
              <div class="bg-green-50 p-4 rounded-lg">
                <h4 class="font-semibold text-gray-800 mb-1">✓ Terrassenreinigung</h4>
                <p class="text-gray-600 text-sm">Professionelle Reinigung von Steinbelägen und Holzterrassen</p>
              </div>
              <div class="bg-green-50 p-4 rounded-lg">
                <h4 class="font-semibold text-gray-800 mb-1">✓ Grünbelagsentfernung</h4>
                <p class="text-gray-600 text-sm">Von Gehwegen, Einfahrten und Terrassen</p>
              </div>
            </div>
          </div>
          <div class="flex-1 lg:max-w-sm">
            <img 
              src="/img/efeu-von-wand-entfernen-6x12.png" 
              alt="Efeu-Entfernung von Hauswand" 
              class="w-full h-auto rounded-xl shadow-lg"
            />
          </div>
        </div>

        <!-- Weggestaltung & Bepflanzung -->
        <div class="flex flex-col lg:flex-row-reverse gap-8 lg:gap-12 items-center mb-16">
          <div class="flex-1">
            <h2 class="text-3xl font-bold text-gray-800 mb-4">Weggestaltung & Bepflanzung</h2>
            <p class="text-gray-600 mb-6">
              Harmonische Gestaltung von Gartenwegen mit passender Bepflanzung 
              für ein stimmiges und einladendes Gesamtbild.
            </p>
            <div class="space-y-3">
              <div class="flex items-center gap-3">
                <svg class="w-5 h-5 text-green-600 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                </svg>
                <span class="text-gray-700">Planung und Umsetzung von Gartenwegen</span>
              </div>
              <div class="flex items-center gap-3">
                <svg class="w-5 h-5 text-green-600 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                </svg>
                <span class="text-gray-700">Passende Bepflanzung entlang der Wege</span>
              </div>
              <div class="flex items-center gap-3">
                <svg class="w-5 h-5 text-green-600 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                </svg>
                <span class="text-gray-700">Beratung für nachhaltige Gartengestaltung</span>
              </div>
            </div>
          </div>
          <div class="flex-1 lg:max-w-sm">
            <img 
              src="/img/eingepflanzt-weg-6x12.png" 
              alt="Schön gestalteter Gartenweg mit Bepflanzung" 
              class="w-full h-auto rounded-xl shadow-lg"
            />
          </div>
        </div>

      </div>
    </section>

    <!-- Vorher-Nachher Beispiele -->
    <section class="bg-gray-50 py-16">
      <div class="container mx-auto px-4 max-w-6xl">
        <h2 class="text-3xl font-bold text-gray-800 text-center mb-12">
          Beispiele unserer Arbeit
        </h2>
        
        <div class="flex flex-col lg:flex-row gap-6">
          <!-- Beispiel 1: Hütte im Garten -->
          <div class="flex-1 bg-white rounded-xl overflow-hidden shadow-lg cursor-pointer hover:shadow-xl transition-all duration-300 group" @click="openModal('huette')">
            <div class="h-48 overflow-hidden relative">
              <img 
                src="/img/vorher-nachher-huette-im-garten-neu.png" 
                alt="Vorher-Nachher: Weg zur Gartenhütte mit neuen Steinplatten" 
                class="w-full h-full object-cover object-center transition-all duration-300 group-hover:blur-sm group-hover:scale-105"
              />
              <div class="absolute inset-0 bg-white bg-opacity-0 group-hover:bg-opacity-20 transition-all duration-300 flex items-center justify-center">
                <div class="bg-white bg-opacity-90 rounded-full p-3 opacity-0 group-hover:opacity-100 transition-all duration-300 transform scale-75 group-hover:scale-100">
                  <svg class="w-6 h-6 text-gray-800" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0zM10 7v3m0 0v3m0-3h3m-3 0H7" />
                  </svg>
                </div>
              </div>
            </div>
            <div class="p-4">
              <h3 class="text-lg font-semibold text-gray-800 mb-2">
                Weggestaltung zur Gartenhütte
              </h3>
              <p class="text-gray-600 text-sm">
                Neuer Steinplattenweg mit kompletter Unkrautentfernung.
              </p>
            </div>
          </div>

          <!-- Beispiel 2: Eingangsbereich -->
          <div class="flex-1 bg-white rounded-xl overflow-hidden shadow-lg cursor-pointer hover:shadow-xl transition-all duration-300 group" @click="openModal('eingang')">
            <div class="h-48 overflow-hidden relative">
              <img 
                src="/img/reinigung-haustuer.png" 
                alt="Professionell gereinigter Eingangsbereich" 
                class="w-full h-full object-cover object-center transition-all duration-300 group-hover:blur-sm group-hover:scale-105"
              />
              <div class="absolute inset-0 bg-white bg-opacity-0 group-hover:bg-opacity-20 transition-all duration-300 flex items-center justify-center">
                <div class="bg-white bg-opacity-90 rounded-full p-3 opacity-0 group-hover:opacity-100 transition-all duration-300 transform scale-75 group-hover:scale-100">
                  <svg class="w-6 h-6 text-gray-800" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0zM10 7v3m0 0v3m0-3h3m-3 0H7" />
                  </svg>
                </div>
              </div>
            </div>
            <div class="p-4">
              <h3 class="text-lg font-semibold text-gray-800 mb-2">
                Eingangsbereich-Reinigung
              </h3>
              <p class="text-gray-600 text-sm">
                Gründliche Reinigung für einen einladenden ersten Eindruck.
              </p>
            </div>
          </div>

          <!-- Beispiel 3: Pflanzen im Garten -->
          <div class="flex-1 bg-white rounded-xl overflow-hidden shadow-lg cursor-pointer hover:shadow-xl transition-all duration-300 group" @click="openModal('pflanzen')">
            <div class="h-48 overflow-hidden relative">
              <img 
                src="/img/vorher-nachher-pflanzen-garten.png" 
                alt="Vorher-Nachher: Verbesserung der Gartenbepflanzung" 
                class="w-full h-full object-cover object-center transition-all duration-300 group-hover:blur-sm group-hover:scale-105"
              />
              <div class="absolute inset-0 bg-white bg-opacity-0 group-hover:bg-opacity-20 transition-all duration-300 flex items-center justify-center">
                <div class="bg-white bg-opacity-90 rounded-full p-3 opacity-0 group-hover:opacity-100 transition-all duration-300 transform scale-75 group-hover:scale-100">
                  <svg class="w-6 h-6 text-gray-800" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0zM10 7v3m0 0v3m0-3h3m-3 0H7" />
                  </svg>
                </div>
              </div>
            </div>
            <div class="p-4">
              <h3 class="text-lg font-semibold text-gray-800 mb-2">
                Gartenbepflanzung optimiert
              </h3>
              <p class="text-gray-600 text-sm">
                Pflanzen bekommen neuen, gesunden Boden und bessere Pflege.
              </p>
            </div>
          </div>
        </div>

        <!-- Modal -->
        <div v-if="selectedModal" class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-black bg-opacity-75" @click="closeModal">
          <div class="relative max-w-4xl max-h-full bg-white rounded-xl overflow-hidden" @click.stop>
            <button @click="closeModal" class="absolute top-4 right-4 z-10 bg-white bg-opacity-90 hover:bg-opacity-100 rounded-full p-2 transition-all">
              <svg class="w-6 h-6 text-gray-800" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
              </svg>
            </button>
            
            <div v-if="selectedModal === 'huette'" class="p-6">
              <img 
                src="/img/vorher-nachher-huette-im-garten-neu.png" 
                alt="Vorher-Nachher: Weg zur Gartenhütte mit neuen Steinplatten" 
                class="w-full h-auto rounded-lg"
              />
              <div class="mt-4">
                <h3 class="text-2xl font-bold text-gray-800 mb-3">Weggestaltung zur Gartenhütte</h3>
                <p class="text-gray-600">
                  <strong>Vorher (links):</strong> Alter, verwachsener Weg mit Unkraut und unebenen Steinen.<br>
                  <strong>Nachher (rechts):</strong> Neuer Steinplattenweg mit kompletter Unkrautentfernung 
                  für einen gepflegten und sicheren Zugang zur Gartenhütte. Die umliegenden Bereiche wurden 
                  ebenfalls gereinigt und neu gestaltet.
                </p>
              </div>
            </div>

            <div v-if="selectedModal === 'eingang'" class="p-6">
              <img 
                src="/img/reinigung-haustuer.png" 
                alt="Professionell gereinigter Eingangsbereich" 
                class="w-full h-auto rounded-lg"
              />
              <div class="mt-4">
                <h3 class="text-2xl font-bold text-gray-800 mb-3">Eingangsbereich-Reinigung</h3>
                <p class="text-gray-600">
                  Professionelle Reinigung des Eingangsbereichs für einen einladenden ersten Eindruck. 
                  Entfernung von Grünbelag, Moos und Verschmutzungen von Gehwegen und Terrassenbereichen. 
                  Das Ergebnis: Ein sauberer, gepflegter Eingang, der Ihre Gäste willkommen heißt.
                </p>
              </div>
            </div>

            <div v-if="selectedModal === 'pflanzen'" class="p-6">
              <img 
                src="/img/vorher-nachher-pflanzen-garten.png" 
                alt="Vorher-Nachher: Verbesserung der Gartenbepflanzung" 
                class="w-full h-auto rounded-lg"
              />
              <div class="mt-4">
                <h3 class="text-2xl font-bold text-gray-800 mb-3">Gartenbepflanzung optimiert</h3>
                <p class="text-gray-600">
                  <strong>Vorher (oben):</strong> Pflanzen in verdichtetem, nährstoffarmem Boden.<br>
                  <strong>Nachher (unten):</strong> Die Pflanzen haben neuen, lockeren und nährstoffreichen Boden erhalten. 
                  Zusätzlich wurde eine optimierte Bewässerung und Düngung durchgeführt, was zu einem deutlich 
                  gesünderen und kräftigeren Pflanzenwachstum führt.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Weitere Leistungen -->
    <section class="py-16">
      <div class="container mx-auto px-4 max-w-6xl">
        <h2 class="text-3xl font-bold text-gray-800 text-center mb-12">
          Weitere Leistungen
        </h2>
        
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
          <div class="text-center p-6 bg-white rounded-lg border shadow-sm">
            <div class="w-12 h-12 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-6 h-6 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
              </svg>
            </div>
            <h3 class="font-semibold text-gray-800 mb-2">Heckenschnitt</h3>
            <p class="text-gray-600 text-sm">Formschnitt für gepflegte Hecken</p>
          </div>
          
          <div class="text-center p-6 bg-white rounded-lg border shadow-sm">
            <div class="w-12 h-12 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-6 h-6 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20 7l-8-4-8 4m16 0l-8 4m8-4v10l-8 4m0-10L4 7m8 4v10M4 7v10l8 4" />
              </svg>
            </div>
            <h3 class="font-semibold text-gray-800 mb-2">Laubbeseitigung</h3>
            <p class="text-gray-600 text-sm">Herbstliche Gartenpflege</p>
          </div>
          
          <div class="text-center p-6 bg-white rounded-lg border shadow-sm">
            <div class="w-12 h-12 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-6 h-6 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3" />
              </svg>
            </div>
            <h3 class="font-semibold text-gray-800 mb-2">Entsorgung</h3>
            <p class="text-gray-600 text-sm">Grünschnitt & Gartenabfälle</p>
          </div>
          
          <div class="text-center p-6 bg-white rounded-lg border shadow-sm">
            <div class="w-12 h-12 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-6 h-6 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z" />
              </svg>
            </div>
            <h3 class="font-semibold text-gray-800 mb-2">Beratung</h3>
            <p class="text-gray-600 text-sm">Individuelle Gartenberatung</p>
          </div>
        </div>
      </div>
    </section>

    <!-- CTA Section -->
    <section class="bg-green-600 text-white py-16">
      <div class="container mx-auto px-4 text-center max-w-4xl">
        <h2 class="text-3xl font-bold mb-6">
          Interessiert an unseren Leistungen?
        </h2>
        <p class="text-lg mb-8 text-green-100">
          Für ein kostenloses Angebot stehe ich jederzeit zur Verfügung. 
          Rufen Sie mich an oder senden Sie mir eine Nachricht.
        </p>
        <div class="flex flex-col sm:flex-row gap-4 justify-center">
          <a 
            href="tel:015209613391"
            class="bg-white text-green-600 hover:bg-gray-100 px-8 py-3 rounded-lg font-semibold transition-colors duration-300 flex items-center justify-center gap-2"
          >
            <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
            </svg>
            0152 09613391
          </a>
          <NuxtLink 
            to="/kontakt"
            class="bg-transparent border-2 border-white text-white hover:bg-white hover:text-green-600 px-8 py-3 rounded-lg font-semibold transition-all duration-300"
          >
            Kontaktformular
          </NuxtLink>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>
import { ref } from 'vue'

// Modal state
const selectedModal = ref(null)

function openModal(modalType) {
  selectedModal.value = modalType
}

function closeModal() {
  selectedModal.value = null
}

// SEO Meta Tags
useHead({
  title: 'Leistungen - Bogdan Garten- und Hausmeisterservice',
  meta: [
    {
      name: 'description',
      content: 'Komplettes Leistungsspektrum: Rasenpflege, Heckenschnitt, Beetpflege, Baumfällung, Terrassenreinigung und mehr. Professioneller Service für Privatgarten, Firmengelände und Wohnanlagen.'
    }
  ]
})
</script>