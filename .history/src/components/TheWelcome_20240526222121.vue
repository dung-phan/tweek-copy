<script setup lang="ts">
const currentDate = new Date(Date.now())

const headerDate = currentDate.toLocaleDateString('default', {
  month: 'long',
  year: 'numeric'
})
</script>

<template>
  <h1 class="pl-3">
    <b>{{ headerDate }}</b>
  </h1>
</template>

<style scoped></style>
