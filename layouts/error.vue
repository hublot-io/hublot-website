<template>
  <main>
    <section>
      <template v-if="error.statusCode === 404">
        <h1 class="title">{{ error.message || 'Page Not Found' }}</h1>
        <h2 class="subtitle">404</h2>
        <p class="mb-4">Pagen on trouvée</p>
      </template>
      <template v-else>
        <h1 class="title">Erreur</h1>
        <p class="mb-4">Le lien ne semble pas valide.</p>
      </template>
      <nav class="mt-12" aria-label="Retour">
        <router-back to="/" class="block" />
      </nav>
    </section>
  </main>
</template>

<script>
export default {
  name: 'error',
  props: ['error']
}
</script>
