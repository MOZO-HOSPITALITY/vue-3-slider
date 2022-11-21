<script setup lang="ts">

interface SliderOptions {
  autoPlay?: boolean;
  loop?: boolean;
  speed?: number;
  pagination?: boolean;
  slidesToScroll?: number;
  currentSlide?: number;
  preventRebound?: boolean;
  slidesPerPage?: number;
}

interface Props {
  title: string;
}

const props = defineProps<Props>()
</script>

<template>
  <h1>{{ title }}</h1>
  <div class="slider">
    <slot></slot>
  </div>
</template>

<style lang="scss">
.slider {
  display: flex;
  background-color: red;
  min-height: 400px;
  flex-direction: row;
}
</style>
