<script setup lang="ts">
interface Props {
  text: string
}

const props = defineProps<Props>()
</script>

<template>
  <h1>{{ text ?? 'empty state' }}</h1>
</template>
