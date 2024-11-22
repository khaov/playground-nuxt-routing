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
    <header class="header">
      Хедер
    </header>
    <aside class="aside">
      <AppNavigation />
    </aside>
    <main class="content">
      <div>
      <NuxtPage />
    </div>
    </main>
    <footer class="footer">
      Футер
    </footer>
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
