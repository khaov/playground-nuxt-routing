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
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>

<style>
  .page{
    display: grid;

    grid-template-areas:
    "header header"
    "aside content"
    "footer footer";
  }

  .header {
    grid-area: header;
  }

  .content {
    grid-area: content;
  }

  .aside {
    grid-area: aside;
  }

  .footer {
    grid-area: footer;
  }

</style>
