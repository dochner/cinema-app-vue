<script setup lang="ts">
// https://github.com/vueuse/head
// you can use this to manipulate the document head in any components,
// they will be rendered correctly in the html results with vite-ssg
useHead({
  title: 'Omdb D',
  meta: [
    { name: 'description', content: 'A Omdb api based front application' },
  ],
})
</script>

<template>
  <router-view />
</template>
