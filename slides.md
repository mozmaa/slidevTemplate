---
# You can also start simply with 'default'
theme: "./slides-theme/theme-default"
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: "./assets/developersBlueBackground.png"
# some information about your slides (markdown enabled)
title: Welcome to Slidev
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: fade-out
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# take snapshot for each slide in the overview
overviewSnapshots: true
---

<div >
  <img class="absolute top-8 left-3 w-44"
     src="./assets/DevelopersLogo.png" alt="Logo" />
  
  <h1> Welcome to Slidev </h1>

  <p>Presentation slides for developers</p>

  <img  class="absolute bottom-2 right-2 w-48 h-64"
      src="./assets/DevelopersRobot.png" alt="Robot" />

</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out

---

<div class="text-center full-screen-background-agenda">
  <img class="absolute top-8 left-3 w-44 content"
     src="./assets/DevelopersLogoWhite.png" alt="Logo" />
  <div class="dim-overlay"></div>
  <h1 class="pt-10 pb-5 content">Agenda</h1>
  <AgendaTitle title='First subject' />
  <AgendaTitle title='Second subject' />
</div>

<script setup>
  import AgendaTitle from './components/AgendaTitles.vue'
</script>

<style scoped>
  @import './css/slide.css'
</style>

---
transition: fade-out
---

<div class="h-inherit">
  <Logo logo="./assets/DevelopersLogoBlack.png"/>
  <div class="flex flex-row -mx-1 h-inherit">
    <EnumCol class="gradient-grey-white-left"
             icon ="📝" 
             title="Column1" 
             paragraphText="Text about the subject from a column title"/>
  </div>
</div>

<style>
  @import './css/slide.css'
</style>

---
transition: fade-out
---

<div class="h-inherit">
  <Logo />
  <div class="flex flex-row -mx-1 h-inherit">
    <EnumCol class="gradient-grey-white-left" 
             icon ="📝" 
             title="Column1" 
             paragraphText="Text about the subject from a column title"/>
    <EnumCol class="gradient-grey-white-right " 
             icon ="🎨" 
             title="Column2" 
             paragraphText="Text about the subject from a column title"/>
  </div>
</div>

<style>
  @import './css/slide.css'
</style>

---
transition: fade-out
---

<div class="h-inherit">
  <Logo logo="./assets/DevelopersLogoBlack.png"/>
  <div class="flex flex-row -mx-1 h-inherit">
    <EnumCol class="gradient-grey-white-left " 
             icon ="📝" 
             title="Column1" 
             paragraphText="Text about the subject from a column title"/>
    <EnumCol class="gradient-grey-white-right " 
             icon ="🎨" 
             title="Column2" 
             paragraphText="Text about the subject from a column title"/>
    <EnumCol class="gradient-grey-white-left "
             icon ="🧑‍💻" 
             title="Column3" 
             paragraphText="Text about the subject from a column title"/>
  </div>
</div>

<style>
  @import './css/slide.css'
</style>

---
transition: fade-out
---

<div class="h-inherit">
  <Logo logo="./assets/DevelopersLogoBlack.png"/>
  <div class="flex flex-row -mx-1 h-inherit">
    <EnumCol class="gradient-grey-white-left " 
             icon ="📝" 
             title="Column1" 
             paragraphText="Text about the subject from a column title"/>
    <EnumCol class="gradient-grey-white-right " 
             icon ="🎨" 
             title="Column2" 
             paragraphText="Text about the subject from a column title"/>
    <EnumCol class="gradient-grey-white-left " 
             icon ="🧑‍💻" 
             title="Column3" 
             paragraphText="Text about the subject from a column title"/>
    <EnumCol class="gradient-grey-white-right " 
             icon ="🤹" 
             title="Column4" 
             paragraphText="Text about the subject from a column title"/>
  </div>
</div>

<style>
  @import './css/slide.css'
</style>

---
transition: fade-out
---

<div class="h-inherit">
  <Logo logo="./assets/DevelopersLogoBlack.png"/>
  <div class="flex flex-row -mx-1 h-inherit">
    <EnumCol class="gradient-grey-white-left " 
             icon ="📝" 
             title="Column1" 
             paragraphText="Text about the subject from a column title"/>
    <EnumCol class="gradient-grey-white-right " 
             icon ="🎨" 
             title="Column2" 
             paragraphText="Text about the subject from a column title"/>
    <EnumCol class="gradient-grey-white-left " 
             icon ="🧑‍💻" 
             title="Column3" 
             paragraphText="Text about the subject from a column title"/>
    <EnumCol class="gradient-grey-white-right  "
             icon ="🤹" 
             title="Column4" 
             paragraphText="Text about the subject from a column title"/>
    <EnumCol class="gradient-grey-white-left " 
             icon ="🎥" 
             title="Column5" 
             paragraphText="Text about the subject from a column title"/>
  </div>
</div>

<style>
  @import './css/slide.css'
</style>

---

<div class="backgroundBlue h-inherit flex justify-center items-center">
  <img class="absolute top-8 left-3 w-44 h-12"
     src="./assets/DevelopersLogo.png" alt="Logo" />
  <div class="absolute top-13 right-0 h-1 w-75% bg-white"></div>
  <div class="gradient-circle text-center flex flex-col justify-center items-center">
    <h1 class='text-black'>Title of a new subject</h1>
    <p class='text-black'>This PR was made to refactor and modularize the CSS codebase. By separating components, utilities, and variables into their respective files, we achieve better maintainability, scalability, and easier collaboration for future changes and enhancements. Additionally, we added support for custom gradients and utility classes to improve code reuse across different components.</p>
  </div>
  <div class="gradient-circle-medium absolute left-0 bottom-15"></div>
  <div class="gradient-circle-medium absolute right-0 bottom-0"></div>
  <div class="gradient-circle-small absolute left-15 bottom-96 "></div>
  <div class="gradient-circle-small absolute right-15 bottom-73 "></div>
  <div class="gradient-circle-small absolute right-40 bottom-96 "></div>
  <!-- <img  class="absolute bottom-2 right-2 w-48 h-64"
      src="./assets/DevelopersRobot.png" alt="Robot" /> -->
</div>

<style>
 @import './css/slide.css'
</style>

---

<div class="gradient-grey-white-left h-inherit justify-center items-center relative">
  <Logo logo="./assets/DevelopersLogoBlack.png"
             title="Code"
             paragraphText="Use code snippets and get the highlighting directly, and even types hover!"/>
  <div class="flex-container div-padding-top flex w-full justify-center items-center ">
    <div class="text-white text-center flex-1">
      <h1>Code explanation</h1>
      <p> // TwoSlash enables TypeScript hover information<br>
          // and errors in markdown code blocks <br>
          // More at https://shiki.style/packages/twoslash</p>
    </div>
  <div class="code-container w-max bg-transparent rounded mr-10 text-xs flex-1 code-block-shadow ">

  ```ts {all} twoslash
  //comments

  import { computed, ref } from "vue";

  const count = ref(0);
  const doubled = computed(() => count.value * 2);

  doubled.value = 2;

  ```

 </div>
  </div>
</div>

<style>
 @import './css/slide.css'
</style>

---

<div class="gradient-grey-white-right h-inherit">
  <Logo title="Code"/>
  <div class="flex-container div-padding-top flex w-full justify-center items-center">
  <div class="code-container  ml-10 w-max bg-transparent rounded flex-1 code-block-shadow ">

  ```ts {all} twoslash 
  //comments

  import { computed, ref } from "vue";

  const count = ref(0);
  const doubled = computed(() => count.value * 2);

  doubled.value = 2;

  ```

 </div>
 <div class="text-white text-center flex-1 mt-10 ">
  <h1>Code explanation</h1>
  <p> // TwoSlash enables TypeScript hover information<br>
      // and errors in markdown code blocks <br>
      // More at https://shiki.style/packages/twoslash</p>
  </div>
  </div>
</div>

<style>
 @import './css/slide.css'
</style>

---

<div class="h-inherit background-blue z-0">
  <img  class="absolute bottom-20 right-98 w-48 h-64 skew-x--20"
      src="./assets/DevelopersRobot.png" alt="Robot" />
  <div class="absolute bg-transparent w-40% h-50% top-2 right-2 z-30">
    <div class="flex flex-col justify-start items-center text-center p-40">
    <h1 class="text-black">Another way to change subject</h1>
    <p class="text-black">Description or some notes</p>
    </div>
  </div>
  <div class="h-inherit">
      <div class="grid-container">
        <div class="block"></div>
        <div class="block block-3d "></div>
      </div>
      <div class="grid-container">
        <div class="block "></div>
        <div class="block"></div>
        <div class="block block-3d"></div>
      </div>
      <div class="grid-container">
        <div class="block "></div>
        <div class="block"></div>
        <div class="block "></div>
        <div class="block block-3d"></div>
      </div>
      <div class="grid-container">
        <div class="block "></div>
        <div class="block "></div>
        <div class="block "></div>
        <div class="block"></div>
        <div class="block block-3d "></div>
      </div>
      <div class="grid-container">
        <div class="block "></div>
        <div class="block"></div>
        <div class="block "></div>
        <div class="block"></div>
        <div class="block "></div>
        <div class="block block-3d "></div>
        <div class="block opacity-0 "></div>
        <div class="block opacity-0 "></div>
        <div class="block block-3d ">
          <img class=" content p-2"
           src="./assets/DevelopersLogoWhite.png" alt="Logo" />
        </div>
      </div>
  </div>
</div>

<style>
 @import './css/slide.css'
</style>

---

<div class="h-inherit background-blue">
    <div class="relative z-10">
      <Logo title="Enumeration Slide"/>
    </div>
    <div class="h-inherit w-1 bg-white absolute left-10 z-0"></div>
    <div class="div-padding-top w-full justify-center items-center">
      <p class="ml-15 text-6xl text-white">What are we enumerating</p>
      <EnumerationLine lineText="Enumeration line 1" />
      <EnumerationLine lineText="Enumeration line 2" />
      <EnumerationLine lineText="Enumeration line 3" /> 
    </div>
    <div class="bg-transparent absolute bottom-15 right-10 w-60 h-60">
      <img class="w-60 h-60" src="./assets/pexels-pixabay-355952.jpg"/>
    </div>
</div>

<style>
 @import './css/slide.css';

</style>

---

<div class="h-inherit bg-cover flex items-center justify-center" :style="{ backgroundImage: `url(${background})` }">
  <img class="absolute top-8 left-3 w-44 h-12" src="./assets/DevelopersLogoBlack.png" alt="Logo" />
  <div class="absolute top-13 right-0 h-1 w-3/4 bg-black"></div>
  <div class="text-center text-black">
    <p class="text-6xl"> End message </p>
    <p> Presented by: </p>
  </div>
  <div class="absolute bottom-13 left-0 h-1 w-3/4 bg-black"></div>
</div>

<script setup>
  import background from './assets/design-space-paper-textured-background.jpg'
</script>

<style>
@import './css/slide.css';
</style>