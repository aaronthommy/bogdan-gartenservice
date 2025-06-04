<template>
  <div class="max-w-4xl mx-auto space-y-8">
    <h2 class="text-3xl font-semibold text-center">Unsere Leistungen</h2>

    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
      <!-- Beispiel-Leistung 1 -->
      <div class="border rounded-lg overflow-hidden shadow-sm">
        <!--<img src="/rasenpflege.jpg" alt="Rasenpflege" class="w-full h-48 object-cover" />-->
        <div class="p-4">
          <h3 class="text-2xl font-medium mb-2">Rasenpflege & -schnitt</h3>
          <p class="text-gray-600">
            Wir übernehmen Mähen, Vertikutieren und Düngen – für einen gesunden und saftig grünen Rasen.
          </p>
        </div>
      </div>

      <!-- Beispiel-Leistung 2 -->
      <div class="border rounded-lg overflow-hidden shadow-sm">
       <!--<img src="/heckenschnitt.jpg" alt="Heckenschnitt" class="w-full h-48 object-cover" />--> 
        <div class="p-4">
          <h3 class="text-2xl font-medium mb-2">Heckenschnitt & Formschnitt</h3>
          <p class="text-gray-600">
            Fachgerechter Schnitt für Hecken und Sträucher – damit Ihr Garten immer gepflegt aussieht.
          </p>
        </div>
      </div>

      <!-- Weitere Leistungen hier ergänzen -->
    </div>
  </div>
</template>

<script setup>
// keine Logik nötig; Bilder liegen später in /public/, z. B. /rasenpflege.jpg, /heckenschnitt.jpg
</script>
