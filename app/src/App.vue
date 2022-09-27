<script setup lang="ts">
import { ref, onMounted } from 'vue'

const msg = ref('message...')

onMounted(() => {
  console.log(msg)
})

</script>

<template>
  <h1>Hello world</h1>
</template>
