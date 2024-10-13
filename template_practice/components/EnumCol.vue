<script setup>
const props = defineProps({
    uniqueClass: {
    type: String,
    default: ''
  },
  icon: {
    type: String,
    default: ''
  },
  title: {
    type: String,
    default: ''
  },
  paragraphText: {
    type: String,
    default: ''
  }
});
</script>

<template>
  <div :class="['flex-1 h-screen text-white border-r border-gray-800', uniqueClass]">
    <h3 class="pt-10 text-center"> {{ icon }}</h3>
    <h3 class="text-center">{{ title }}</h3>
    <p class="text-center p-4">{{ paragraphText }}</p>
  </div>
</template>