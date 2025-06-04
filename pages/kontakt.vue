<template>
  <div class="py-12">
    <!-- Header -->
    <section class="text-center mb-16">
      <h1 class="text-4xl md:text-5xl font-bold text-gray-800 mb-6">
        Kontakt
      </h1>
      <p class="text-xl text-gray-600 max-w-3xl mx-auto">
        Für ein kostenloses Angebot stehe ich jederzeit zur Verfügung. 
        Rufen Sie mich an oder senden Sie mir eine Nachricht.
      </p>
    </section>

    <div class="container mx-auto px-4">
      <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
        <!-- Kontaktinformationen -->
        <div class="space-y-8">
          <div>
            <h2 class="text-2xl font-bold text-gray-800 mb-6">
              Kontaktinformationen
            </h2>
            
            <!-- Telefon -->
            <div class="flex items-start gap-4 p-6 bg-white rounded-xl shadow-sm border border-gray-100 mb-6">
              <div class="w-12 h-12 bg-green-100 rounded-full flex items-center justify-center flex-shrink-0">
                <svg class="w-6 h-6 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
                </svg>
              </div>
              <div>
                <h3 class="text-lg font-semibold text-gray-800 mb-2">Telefon</h3>
                <a 
                  href="tel:015209613391" 
                  class="text-2xl font-bold text-green-600 hover:text-green-700 transition-colors"
                >
                  0152 09613391
                </a>
                <p class="text-gray-600 mt-1">
                  Montag - Samstag: 8:00 - 18:00 Uhr
                </p>
              </div>
            </div>

            <!-- Service-Gebiete -->
            <div class="flex items-start gap-4 p-6 bg-white rounded-xl shadow-sm border border-gray-100 mb-6">
              <div class="w-12 h-12 bg-green-100 rounded-full flex items-center justify-center flex-shrink-0">
                <svg class="w-6 h-6 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                </svg>
              </div>
              <div>
                <h3 class="text-lg font-semibold text-gray-800 mb-2">Service-Gebiet</h3>
                <p class="text-gray-600">
                  Hannover und Umgebung<br>
                  Laatzen, Hemmingen, Pattensen<br>
                  Sehnde, Lehrte und weitere Orte
                </p>
              </div>
            </div>

            <!-- Angebot -->
            <div class="flex items-start gap-4 p-6 bg-white rounded-xl shadow-sm border border-gray-100">
              <div class="w-12 h-12 bg-green-100 rounded-full flex items-center justify-center flex-shrink-0">
                <svg class="w-6 h-6 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z" />
                </svg>
              </div>
              <div>
                <h3 class="text-lg font-semibold text-gray-800 mb-2">Kostenloses Angebot</h3>
                <p class="text-gray-600">
                  Unverbindliche Besichtigung und Kostenvoranschlag. 
                  Faire Preise und transparente Abrechnung.
                </p>
              </div>
            </div>
          </div>

          <!-- Unsere Services -->
          <div>
            <h3 class="text-xl font-semibold text-gray-800 mb-4">
              Unsere Services im Überblick
            </h3>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
              <div class="flex items-center gap-2 text-gray-600">
                <svg class="w-4 h-4 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                </svg>
                Rasenpflege
              </div>
              <div class="flex items-center gap-2 text-gray-600">
                <svg class="w-4 h-4 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                </svg>
                Heckenschnitt
              </div>
              <div class="flex items-center gap-2 text-gray-600">
                <svg class="w-4 h-4 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                </svg>
                Beetpflege
              </div>
              <div class="flex items-center gap-2 text-gray-600">
                <svg class="w-4 h-4 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                </svg>
                Terrassenreinigung
              </div>
              <div class="flex items-center gap-2 text-gray-600">
                <svg class="w-4 h-4 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                </svg>
                Baumfällung
              </div>
              <div class="flex items-center gap-2 text-gray-600">
                <svg class="w-4 h-4 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7" />
                </svg>
                Unkrautentfernung
              </div>
            </div>
          </div>
        </div>

        <!-- Kontaktformular -->
        <div class="bg-white p-8 rounded-xl shadow-lg border border-gray-100">
          <h2 class="text-2xl font-bold text-gray-800 mb-6">
            Nachricht senden
          </h2>
          
          <form @submit.prevent="submitForm" class="space-y-6">
            <!-- Name -->
            <div>
              <label for="name" class="block text-sm font-medium text-gray-700 mb-2">
                Vor- und Nachname *
              </label>
              <input
                v-model="form.name"
                type="text"
                id="name"
                required
                class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-green-500 focus:border-green-500 transition-colors"
                placeholder="Max Mustermann"
              />
            </div>

            <!-- E-Mail -->
            <div>
              <label for="email" class="block text-sm font-medium text-gray-700 mb-2">
                E-Mail-Adresse *
              </label>
              <input
                v-model="form.email"
                type="email"
                id="email"
                required
                class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-green-500 focus:border-green-500 transition-colors"
                placeholder="max@mustermann.de"
              />
            </div>

            <!-- Telefon -->
            <div>
              <label for="telefon" class="block text-sm font-medium text-gray-700 mb-2">
                Telefonnummer (optional)
              </label>
              <input
                v-model="form.telefon"
                type="tel"
                id="telefon"
                class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-green-500 focus:border-green-500 transition-colors"
                placeholder="0511 123456"
              />
            </div>

            <!-- Service -->
            <div>
              <label for="service" class="block text-sm font-medium text-gray-700 mb-2">
                Gewünschte Leistung
              </label>
              <select
                v-model="form.service"
                id="service"
                class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-green-500 focus:border-green-500 transition-colors"
              >
                <option value="">Bitte wählen</option>
                <option value="rasenpflege">Rasenpflege</option>
                <option value="heckenschnitt">Heckenschnitt</option>
                <option value="beetpflege">Beetpflege</option>
                <option value="terrassenreinigung">Terrassenreinigung</option>
                <option value="baumfaellung">Baumfällung / Baumpflege</option>
                <option value="unkrautentfernung">Unkrautentfernung</option>
                <option value="laubbeseitigung">Laubbeseitigung</option>
                <option value="efeu-entfernung">Efeu-Entfernung</option>
                <option value="sonstiges">Sonstiges</option>
              </select>
            </div>

            <!-- Nachricht -->
            <div>
              <label for="nachricht" class="block text-sm font-medium text-gray-700 mb-2">
                Ihre Nachricht *
              </label>
              <textarea
                v-model="form.nachricht"
                id="nachricht"
                rows="5"
                required
                class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-green-500 focus:border-green-500 transition-colors resize-none"
                placeholder="Beschreiben Sie hier Ihr Anliegen und die gewünschten Arbeiten..."
              ></textarea>
            </div>

            <!-- Submit Button -->
            <button
              type="submit"
              :disabled="isSubmitting"
              class="w-full bg-green-600 hover:bg-green-700 disabled:bg-gray-400 text-white px-6 py-4 rounded-lg font-semibold text-lg transition-colors duration-300 flex items-center justify-center gap-2"
            >
              <svg v-if="isSubmitting" class="w-5 h-5 animate-spin" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 4v5h.582m15.356 2A8.001 8.001 0 004.582 9m0 0H9m11 11v-5h-.581m0 0a8.003 8.003 0 01-15.357-2m15.357 2H15" />
              </svg>
              <svg v-else class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 19l9 2-9-18-9 18 9-2zm0 0v-8" />
              </svg>
              {{ isSubmitting ? 'Wird gesendet...' : 'Nachricht senden' }}
            </button>

            <p class="text-sm text-gray-500 text-center">
              * Pflichtfelder. Ihre Daten werden vertraulich behandelt.
            </p>
          </form>
        </div>
      </div>

      <!-- Direkter Kontakt CTA -->
      <section class="mt-16 bg-green-50 rounded-2xl p-8 text-center">
        <h2 class="text-2xl font-bold text-gray-800 mb-4">
          Lieber direkten Kontakt?
        </h2>
        <p class="text-gray-600 mb-6">
          Rufen Sie mich einfach an - ich berate Sie gerne persönlich und erstelle 
          Ihnen ein kostenloses Angebot vor Ort.
        </p>
        <a 
          href="tel:015209613391"
          class="inline-flex items-center gap-3 bg-green-600 hover:bg-green-700 text-white px-8 py-4 rounded-lg font-semibold text-lg transition-colors duration-300"
        >
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
          </svg>
          0152 09613391
        </a>
      </section>
    </div>
  </div>
</template>

<script setup lang="ts">
import { reactive, ref } from 'vue'

const form = reactive({
  name: '',
  email: '',
  telefon: '',
  service: '',
  nachricht: '',
})

const isSubmitting = ref(false)

async function submitForm() {
  isSubmitting.value = true
  
  try {
    // Hier würde später die echte API-Integration stattfinden
    await new Promise(resolve => setTimeout(resolve, 1500)) // Simuliert API-Aufruf
    
    console.log('Kontaktformular abgeschickt:', { ...form })
    
    // Erfolgs-Nachricht
    alert('Vielen Dank für Ihre Nachricht! Ich melde mich in Kürze bei Ihnen.')
    
    // Formular zurücksetzen
    form.name = ''
    form.email = ''
    form.telefon = ''
    form.service = ''
    form.nachricht = ''
    
  } catch (error) {
    console.error('Fehler beim Senden:', error)
    alert('Entschuldigung, beim Senden ist ein Fehler aufgetreten. Bitte versuchen Sie es erneut oder rufen Sie mich direkt an.')
  } finally {
    isSubmitting.value = false
  }
}

// SEO Meta Tags
useHead({
  title: 'Kontakt - Bogdan Garten- und Hausmeisterservice',
  meta: [
    {
      name: 'description',
      content: 'Kontaktieren Sie Bogdan Garten- und Hausmeisterservice für ein kostenloses Angebot. Tel: 0152 09613391. Service in Hannover und Umgebung.'
    }
  ]
})
</script>