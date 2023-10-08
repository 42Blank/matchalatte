<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>
<template>
  <div class="details">
    <h3>{{ msg }}</h3>
  </div>
</template>
