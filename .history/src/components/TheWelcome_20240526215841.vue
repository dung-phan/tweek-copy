<script setup lang="ts">
const currentDate = new Date(Date.now())

const headerDate = currentDate.toLocaleDateString('default', {
  month: 'long',
  year: 'numeric'
})
</script>

<template></template>
