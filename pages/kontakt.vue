<template>
  <div class="max-w-lg mx-auto">
    <h2 class="text-3xl font-semibold mb-6 text-center">Kontakt</h2>
    <form @submit.prevent="submitForm" class="space-y-4">
      <div>
        <label for="name" class="block mb-1 font-medium">Name</label>
        <input
          v-model="form.name"
          type="text"
          id="name"
          class="w-full border rounded px-3 py-2"
          required
        />
      </div>
      <div>
        <label for="email" class="block mb-1 font-medium">E-Mail</label>
        <input
          v-model="form.email"
          type="email"
          id="email"
          class="w-full border rounded px-3 py-2"
          required
        />
      </div>
      <div>
        <label for="nachricht" class="block mb-1 font-medium">Nachricht</label>
        <textarea
          v-model="form.nachricht"
          id="nachricht"
          rows="5"
          class="w-full border rounded px-3 py-2"
          required
        ></textarea>
      </div>
      <button
        type="submit"
        class="bg-green-600 text-white px-6 py-2 rounded hover:bg-green-700 transition"
      >
        Absenden
      </button>
    </form>
  </div>
</template>

<script setup lang="ts">
import { reactive } from 'vue'

const form = reactive({
  name: '',
  email: '',
  nachricht: '',
})

function submitForm() {
  // Hier würdest du später API-Call oder E-Mail-Versand integrieren.
  console.log('Form abgeschickt:', { ...form })
  alert('Vielen Dank für Ihre Nachricht! Wir melden uns in Kürze.')
  form.name = ''
  form.email = ''
  form.nachricht = ''
}
</script>
