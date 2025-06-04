<template>
  <footer class="bg-gray-800 text-white">
    <div class="container mx-auto px-4 py-12">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
        <!-- Unternehmen -->
        <div>
          <div class="flex items-center gap-3 mb-6">
            <img 
              src="/img/bogdan-garten-hausmeisterservice-logo-500x500.png" 
              alt="Bogdan Logo" 
              class="h-10 w-10"
            />
            <div>
              <h3 class="text-lg font-bold">Bogdan</h3>
              <p class="text-sm text-gray-300">Garten- & Hausmeisterservice</p>
            </div>
          </div>
          <p class="text-gray-300 text-sm">
            Ihr zuverlässiger Partner für professionelle Gartenpflege 
            und Hausmeisterservice in Hannover und Umgebung.
          </p>
        </div>

        <!-- Leistungen -->
        <div>
          <h4 class="text-lg font-semibold mb-4">Leistungen</h4>
          <ul class="space-y-2 text-sm text-gray-300">
            <li>
              <NuxtLink to="/leistungen" class="hover:text-green-400 transition-colors">
                Rasenpflege
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="/leistungen" class="hover:text-green-400 transition-colors">
                Heckenschnitt
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="/leistungen" class="hover:text-green-400 transition-colors">
                Beetpflege
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="/leistungen" class="hover:text-green-400 transition-colors">
                Terrassenreinigung
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="/leistungen" class="hover:text-green-400 transition-colors">
                Baumfällung & Baumpflege
              </NuxtLink>
            </li>
          </ul>
        </div>

        <!-- Navigation -->
        <div>
          <h4 class="text-lg font-semibold mb-4">Navigation</h4>
          <ul class="space-y-2 text-sm text-gray-300">
            <li>
              <NuxtLink to="/" class="hover:text-green-400 transition-colors">
                Home
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="/ueber" class="hover:text-green-400 transition-colors">
                Über uns
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="/leistungen" class="hover:text-green-400 transition-colors">
                Leistungen
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="/kontakt" class="hover:text-green-400 transition-colors">
                Kontakt
              </NuxtLink>
            </li>
          </ul>
        </div>

        <!-- Kontakt -->
        <div>
          <h4 class="text-lg font-semibold mb-4">Kontakt</h4>
          <div class="space-y-3 text-sm text-gray-300">
            <a 
              href="tel:015209613391" 
              class="flex items-center gap-2 hover:text-green-400 transition-colors"
            >
              <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
              </svg>
              0152 09613391
            </a>
            <div class="flex items-start gap-2">
              <svg class="w-4 h-4 mt-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
              </svg>
              <div>
                <p>Hannover und Umgebung</p>
                <p>Laatzen, Hemmingen, Pattensen</p>
              </div>
            </div>
            <div class="pt-2">
              <p class="text-xs text-gray-400">
                Mo - Sa: 8:00 - 18:00 Uhr
              </p>
            </div>
          </div>
        </div>
      </div>

      <!-- Trennlinie -->
      <div class="border-t border-gray-700 mt-8 pt-8">
        <div class="flex flex-col md:flex-row justify-between items-center gap-4">
          <p class="text-sm text-gray-400">
            © 2025 Bogdan Garten- und Hausmeisterservice. Alle Rechte vorbehalten.
          </p>
          <div class="flex gap-6 text-sm text-gray-400">
            <NuxtLink 
              to="/datenschutz" 
              class="hover:text-green-400 transition-colors"
            >
              Datenschutz
            </NuxtLink>
            <NuxtLink 
              to="/impressum" 
              class="hover:text-green-400 transition-colors"
            >
              Impressum
            </NuxtLink>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script setup>
// Footer-Komponente für moderne Darstellung
</script>