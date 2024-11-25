<template>
  <div class="page__wrapper">
    <div class="page__header">
      <AppHeader />
    </div>

    <div class="page__content">
      <main>
        <slot />
      </main>
    </div>

    <div class="page__footer">
      <AppFooter />
    </div>
  </div>
</template>

