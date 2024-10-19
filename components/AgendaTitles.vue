<script setup>
import '../css/slide.css'

const props = defineProps({
    uniqueClass: {
    type: String,
    default: ''
  },
  title: {
    type: String,
    default: ''
  }
});
</script>

<template>
  <p class="underline decoration-dotted content">
    {{ title }}
  </p>
</template>