<script setup lang="ts">
const currentDate = new Date(Date.now())

const headerDate = currentDate.toLocaleDateString('default', {
  month: 'long',
  year: 'numeric'
})
</script>

<template>
  <h2>{{ headerDate }}</h2>
</template>
