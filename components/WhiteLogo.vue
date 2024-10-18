<script setup>
import '../css/slide.css'
import { sharedString } from '../snippets/shared-strings';


const props = defineProps({
  uniqueClass: {
    type: String,
    default: ''
  },
  title: {
    type: String,
    default: sharedString.title
  },
  paragraphText: {
    type: String,
    default: sharedString.paragraphText
  }
  });
</script>

<!-- <template>
    <div class="w-full h-24 customColor flex items-center justify-between ">
      <div class="flex flex-col items-start justify-center ">
      <h1 :class= "['pl-4 gradient-black-white ', uniqueClass ]">{{ title }}</h1>
      <p class="pl-4 customP">{{ paragraphText }}</p>
      </div>
      <img class="w-44 h-12 pr-4"
     src="../assets/DevelopersLogoWhite.png" alt="Logo" />
  </div>
  
</template> -->

<template>
  <div class="w-full h-24 customColor flex items-center justify-between ">
   <div class=" bg-white paper-box items-center mx-5 w-full">
        <h1 :class= "['gradient-black-grey h1-margin-zero', uniqueClass ]">{{ title }}</h1>
      </div>
      <img class="w-44 h-12 pr-4"
     src="../assets/DevelopersLogoWhite.png" alt="Logo" />
  </div>
</template>
