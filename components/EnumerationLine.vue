<script setup>
import '../css/slide.css'
import { sharedString } from '../snippets/shared-strings';


const props = defineProps({
  uniqueClass: {
    type: String,
    default: ''
  },
  lineText: {
    type: String,
    default: ''
  },
  });
</script>

<template>
  <div class="mt-10 ml-10 flex gap-6 items-center">
    <div class="triangle-right"></div>
    <p class="text-3xl text-white">{{ lineText }}</p>
  </div>
</template>