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
  <div :class="['flex-1 text-white h-inherit ', uniqueClass]">
    <h3 class="pt-10 mt-20 text-center text-black"> {{ icon }}</h3>
    <h3 class="text-center text-black">{{ title }}</h3>
    <p class="text-center p-4 text-black" >{{ paragraphText }}</p>
  </div>
</template>