<script setup lang="ts">
  const router = useRouter()
  const routes = router.getRoutes();
</script>

<template>
  <ul>
    <li v-for="route in routes" :key="route.path">
      <NuxtLink :to="route.path" >
        {{ route.name }}
      </NuxtLink>
    </li>
  </ul>
</template>
