<script setup lang="ts">
// interface SlideProps {
//
// }
//
// const props = defineProps<SlideProps>()
</script>

<template>
  <div class="slide">
    <slot></slot>
  </div>
</template>

<style lang="scss">
  .slide {
    min-height:100%;
    flex-grow: 1;
    margin: 8px;
    background-color: grey;
  }
</style>
