<script setup lang="ts">
  import { ProjectName } from '~/constants';

  useHead({
    title: `${ProjectName}`,

    meta: [
      { name: 'description', content: 'Приложение для изучения Nuxt Routing' },
      { name: 'keywords', content: 'Vue, Nuxt, Routing' }
    ],
    link: [
      { rel: "icon", href: "/favicon.ico" },
    ],
  })
</script>

<template>
  <div class="page">
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>

<style>
  @import url("~/assets/css/main.css");
</style>
