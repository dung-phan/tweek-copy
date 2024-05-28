<script setup lang="ts">
import { defineProps } from 'vue'

const { day } = defineProps<{
  day: string
}>()
</script>
<template>
  <div class="flex justify-between pb-3 border-b-2 border-black">
      <p class="text-[21px]">
        <b>27.05</b>
      </p>
      <p class="text-[21px] text-gray-300">
        {{ day }}
      </p>
  </div>
</template>
