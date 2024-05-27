<script setup lang="ts">
const currentDate = new Date(Date.now())

const headerDate = currentDate.toLocaleDateString('default', {
  month: 'long',
  year: 'numeric'
})
</script>

<template>
  <p class="text-2xl">
    <b>{{ headerDate }}</b>
  </p>
</template>

<style scoped></style>
