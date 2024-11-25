<template>
  <div class="page__wrapper">
    <div class="page__header">
      <AppHeader />
    </div>

    <div class="page__content">
      <aside>
        <AppNavigation />
      </aside>
      <main>
        <slot />
      </main>
    </div>

    <div class="page__footer">
      <AppFooter />
    </div>
  </div>
</template>
