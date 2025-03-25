<script setup lang="ts">
import { RangeDatePicker } from '@/components/ui/range-date-picker'

const onUpdateDate = (value: any) => {
  console.log('value', value);
}
</script>

<template>
  <RangeDatePicker :initial-date="['2025-02-03', '2025-02-03']" @update="onUpdateDate" />
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
