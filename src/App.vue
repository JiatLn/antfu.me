<script setup lang="ts">
useHead({
  meta: [
    { property: 'og:title', content: 'Anthony Fu' },
    { property: 'og:image', content: 'https://antfu.me/og-icon.png' },
    { name: 'description', content: 'Anthony Fu\'s Portfolio' },
    { name: 'twitter:card', content: 'summary' },
    { name: 'twitter:creator', content: '@antfu7' },
  ],
})
</script>

<template>
  <NavBar />
  <main class="px-7 py-10">
    <router-view />
    <Footer />
  </main>
</template>
