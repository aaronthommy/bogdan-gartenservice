<template>
  <nav class="bg-white shadow-lg sticky top-0 z-50 border-b border-gray-100">
    <div class="container mx-auto px-4">
      <div class="flex justify-between items-center py-4">
        <!-- Logo als Home Button -->
        <NuxtLink 
          to="/"
          class="flex items-center space-x-3 hover:opacity-80 transition-opacity duration-200 group"
        >
          <div class="relative">
            <img 
              src="/img/bogdan-garten-hausmeisterservice-logo-500x500.png" 
              alt="Bogdan Gartenservice Logo"
              class="h-12 w-12 object-contain transition-transform duration-200 group-hover:scale-105"
            >
          </div>
          <div>
            <h2 class="text-xl font-bold text-gray-900 group-hover:text-green-600 transition-colors duration-200">
              Bogdan
            </h2>
            <p class="text-sm text-green-600 font-medium">
              Garten & Hausmeisterservice
            </p>
          </div>
        </NuxtLink>

        <!-- Desktop Navigation - sichtbar ab md (768px+) -->
        <ul class="hidden  md:flex items-center space-x-8">
          <li>
            <NuxtLink
              to="/"
              class="text-gray-700 hover:text-green-600 font-medium transition-all duration-200 relative group px-2 py-1"
              active-class="text-green-600"
              exact
            >
              Home
              <span class="absolute bottom-0 left-1/2 transform -translate-x-1/2 w-0 h-0.5 bg-green-600 transition-all duration-200 group-hover:w-full"></span>
            </NuxtLink>
          </li>
          <li>
            <NuxtLink
              to="/ueber"
              class="text-gray-700 hover:text-green-600 font-medium transition-all duration-200 relative group px-2 py-1"
              active-class="text-green-600"
            >
              Über uns
              <span class="absolute bottom-0 left-1/2 transform -translate-x-1/2 w-0 h-0.5 bg-green-600 transition-all duration-200 group-hover:w-full"></span>
            </NuxtLink>
          </li>
          <li>
            <NuxtLink
              to="/leistungen"
              class="text-gray-700 hover:text-green-600 font-medium transition-all duration-200 relative group px-2 py-1"
              active-class="text-green-600"
            >
              Leistungen
              <span class="absolute bottom-0 left-1/2 transform -translate-x-1/2 w-0 h-0.5 bg-green-600 transition-all duration-200 group-hover:w-full"></span>
            </NuxtLink>
          </li>
          <li>
            <NuxtLink
              to="/kontakt"
              class="bg-green-600 hover:bg-green-700 text-white px-6 py-3 rounded-lg font-medium transition-all duration-200 shadow-md hover:shadow-lg transform hover:-translate-y-0.5"
            >
              Kontakt
            </NuxtLink>
          </li>
        </ul>

        <!-- Mobile Menu Button - sichtbar nur unter md (768px) -->
        <button 
          @click="toggleMobileMenu"
          class="block md:hidden relative flex flex-col justify-center items-center w-10 h-10 p-2 rounded-lg hover:bg-gray-100 transition-colors duration-200"
          :aria-expanded="mobileMenuOpen"
          aria-label="Menu"
        >
          <span 
            class="w-6 h-0.5 bg-gray-700 transition-all duration-300 transform origin-center"
            :class="mobileMenuOpen ? 'rotate-45 translate-y-0' : '-translate-y-1.5'"
          ></span>
          <span 
            class="w-6 h-0.5 bg-gray-700 transition-all duration-300"
            :class="mobileMenuOpen ? 'opacity-0 scale-0' : 'opacity-100 scale-100'"
          ></span>
          <span 
            class="w-6 h-0.5 bg-gray-700 transition-all duration-300 transform origin-center"
            :class="mobileMenuOpen ? '-rotate-45 translate-y-0' : 'translate-y-1.5'"
          ></span>
        </button>
      </div>

      <!-- Mobile Navigation - sichtbar nur unter md (768px) -->
      <div 
        class="block md:hidden overflow-hidden transition-all duration-300 ease-in-out"
        :class="mobileMenuOpen ? 'max-h-96 opacity-100' : 'max-h-0 opacity-0'"
      >
        <div class="px-4 py-4 bg-white border-t border-gray-100">
          <ul class="space-y-3">
            <li>
              <NuxtLink
                to="/"
                @click="closeMobileMenu"
                class="flex items-center text-gray-700 hover:text-green-600 font-medium py-3 px-4 rounded-lg hover:bg-green-50 transition-all duration-200"
                active-class="text-green-600 bg-green-50"
                exact
              >
                <svg class="w-5 h-5 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"></path>
                </svg>
                Home
              </NuxtLink>
            </li>
            <li>
              <NuxtLink
                to="/ueber"
                @click="closeMobileMenu"
                class="flex items-center text-gray-700 hover:text-green-600 font-medium py-3 px-4 rounded-lg hover:bg-green-50 transition-all duration-200"
                active-class="text-green-600 bg-green-50"
              >
                <svg class="w-5 h-5 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"></path>
                </svg>
                Über uns
              </NuxtLink>
            </li>
            <li>
              <NuxtLink
                to="/leistungen"
                @click="closeMobileMenu"
                class="flex items-center text-gray-700 hover:text-green-600 font-medium py-3 px-4 rounded-lg hover:bg-green-50 transition-all duration-200"
                active-class="text-green-600 bg-green-50"
              >
                <svg class="w-5 h-5 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11H5m14 0a2 2 0 012 2v6a2 2 0 01-2 2H5a2 2 0 01-2-2v-6a2 2 0 012-2m14 0V9a2 2 0 00-2-2M5 11V9a2 2 0 012-2m0 0V5a2 2 0 012-2h6a2 2 0 012 2v2M7 7h10"></path>
                </svg>
                Leistungen
              </NuxtLink>
            </li>
            <li class="pt-2">
              <NuxtLink
                to="/kontakt"
                @click="closeMobileMenu"
                class="flex items-center justify-center bg-green-600 hover:bg-green-700 text-white px-6 py-4 rounded-lg font-medium transition-all duration-200 text-center shadow-md hover:shadow-lg"
              >
                <svg class="w-5 h-5 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
                </svg>
                Kontakt
              </NuxtLink>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </nav>
</template>

<script setup>
import { ref, onMounted, onUnmounted } from 'vue'

const mobileMenuOpen = ref(false)

function toggleMobileMenu() {
  mobileMenuOpen.value = !mobileMenuOpen.value
  console.log('Mobile menu toggled:', mobileMenuOpen.value) // Debug-Log
}

function closeMobileMenu() {
  mobileMenuOpen.value = false
}

// Schließe das Menü bei Escape-Taste
function handleKeydown(event) {
  if (event.key === 'Escape' && mobileMenuOpen.value) {
    closeMobileMenu()
  }
}

// Schließe das Menü bei Resize (falls User von Mobile zu Desktop wechselt)
function handleResize() {
  if (window.innerWidth >= 768 && mobileMenuOpen.value) {
    closeMobileMenu()
  }
}

onMounted(() => {
  document.addEventListener('keydown', handleKeydown)
  window.addEventListener('resize', handleResize)
})

onUnmounted(() => {
  document.removeEventListener('keydown', handleKeydown)
  window.removeEventListener('resize', handleResize)
})
</script>

<style scoped>
/* Smooth scrolling für bessere UX */
html {
  scroll-behavior: smooth;
}

/* Aktive Links Styling */
.router-link-active span::after {
  content: '';
  position: absolute;
  bottom: -2px;
  left: 50%;
  transform: translateX(-50%);
  width: 100%;
  height: 2px;
  background-color: #059669;
}
</style>