<script setup lang="ts">
  import { ProjectName } from '~/constants';

  useHead({
    title: `${ProjectName} | Личный кабинет`
  })

  definePageMeta({
    layout: 'detail'
  })
</script>

<template>
  <h1>Личный кабинет пользователя</h1>

  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce et mi commodo, lobortis lacus eget, blandit ex. Nunc auctor sapien ut quam vestibulum gravida. Aenean rutrum justo sed nisl elementum bibendum. Phasellus vehicula elit turpis, nec mattis diam accumsan eget. Sed mattis, magna et mattis luctus, ex leo tristique nunc, nec auctor dui diam in tortor. Ut eget metus eget est interdum venenatis ut et nisl. Nullam ac dui augue. Sed finibus lobortis mi aliquet condimentum. Quisque non odio eros. Sed malesuada tortor nec dolor molestie molestie. Cras imperdiet dignissim purus, ut sagittis massa elementum placerat.</p>
</template>
