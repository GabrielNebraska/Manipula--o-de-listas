<script setup>
const items = [
  { id: '1', name: 'item1' },
  { id: '2', name: 'item2' },
  { id: '3', name: 'item3' }
]
</script>
<template>
  <div v-for="item in items" :key="item.id">
    {{ item.name }}>
    <p>{{ item.name }}</p>
  </div>
</template>
