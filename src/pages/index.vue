<script setup lang="ts">
  import { useHead } from 'unhead'
  import TheWelcome from '@/components/TheWelcome.vue'

  definePage({
    name: 'home',
    // alias: ['home'],
    meta: {
      title: 'Home',
      navOrder: 1,
    },
  })

  useHead({
    title: 'Home',
  })
</script>
<template>
  <main>
    <TheWelcome />
  </main>
</template>
<style scoped></style>
