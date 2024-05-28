<script setup lang="ts">
import CurrentDateMonth from '../components/CurrentDateMonth.vue'
import DayBlock from '../components/DayBlock.vue'
const daysInWeek = ['Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat']
</script>

<template>
  <header class="p-6 pb-12">
    <CurrentDateMonth />
  </header>
  <section class="p-6 flex flex-wrap gap-7">
    <div v-for="day in daysInWeek" :key="day" class="flex-1">
      <DayBlock :day="day" />
    </div>
  </section>
</template>
