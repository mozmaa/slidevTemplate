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
  <img class="absolute top-8 left-3 w-44 h-12"
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
  <img class="absolute top-8 left-3 w-44 h-12 content"
     src="./assets/DevelopersLogoWhite.png" alt="Logo" />
  <div class="dim-overlay"></div>
  <h1 class="pt-10 pb-5 content">Agenda</h1>
  <p  class="underline decoration-dotted content">What is Slidev?</p>
  <p class="underline decoration-dotted content">Code</p>
</div>

<style scoped>
  @import './css/slide.css'
</style>

---
transition: fade-out
---

<div>
  <WhiteLogo />
  <div class="flex flex-row -mx-1">
    <EnumCol class="colColor1 "
             icon ="📝" 
             title="Text-based" 
             paragraphText="Focus on the content with Markdown, and then style them later" />
  </div>
</div>

<script setup>
  import EnumCol from './components/EnumCol.vue'
  import WhiteLogo from './components/WhiteLogo.vue'
</script>

<style>
  @import './css/slide.css'
</style>

---
transition: fade-out
---

<div>
  <WhiteLogo uniqueClass='gradient-black-white'/>
  <div class="flex flex-row -mx-1">
    <EnumCol class="colColor1" 
             icon ="📝" 
             title="Text-based" 
             paragraphText="Focus on the content with Markdown, and then style them later"/>
    <!-- <div class="w-0.5 bg-white"></div> -->
    <EnumCol class="colColor2 " 
             icon ="🎨" 
             title="Themable" 
             paragraphText="Themes can be shared and re-used as npm packages"/>
  </div>
</div>

<script setup>
  import EnumCol from './components/EnumCol.vue'
  import WhiteLogo from './components/WhiteLogo.vue'
</script>

<style>
  @import './css/slide.css'
</style>

---
transition: fade-out
---

<div>
  <WhiteLogo uniqueClass='gradient-black-white'/>
  <div class="flex flex-row -mx-1">
    <EnumCol class="colColor1 " 
             icon ="📝" 
             title="Text-based" 
             paragraphText="Focus on the content with Markdown, and then style them later"/>
    <!-- <div class="w-0.5 bg-white"></div> -->
    <EnumCol class="colColor2 " 
             icon ="🎨" 
             title="Themable" 
             paragraphText="Themes can be shared and re-used as npm packages"/>
    <!-- <div class="w-0.5 bg-white"></div> -->
    <EnumCol class="colColor1 "
             icon ="🧑‍💻" 
             title="Developer Friendly" 
             paragraphText="Code highlighting, live coding with autocompletion" />
  </div>
</div>

<script setup>
  import EnumCol from './components/EnumCol.vue'
  import WhiteLogo from './components/WhiteLogo.vue'
</script>

<style>
  @import './css/slide.css'
</style>

---
transition: fade-out
---

<div>
  <WhiteLogo uniqueClass='gradient-black-white'/>
  <div class="flex flex-row -mx-1">
    <EnumCol class="colColor1 " 
             icon ="📝" 
             title="Text-based" 
             paragraphText="Focus on the content with Markdown, and then style them later"/>
    <!-- <div class="w-0.5 bg-white"></div> -->
    <EnumCol class="colColor2 " 
             icon ="🎨" 
             title="Themable" 
             paragraphText="Themes can be shared and re-used as npm packages"/>
    <!-- <div class="w-0.5 bg-white"></div> -->
    <EnumCol class="colColor1 " 
             icon ="🧑‍💻" 
             title="Developer Friendly" 
             paragraphText="Code highlighting, live coding with autocompletion"/>
    <!-- <div class="w-0.5 bg-white"></div> -->
    <EnumCol class="colColor2 " 
             icon ="🤹" 
             title="Interactive" 
             paragraphText="Embed Vue components to enhance your expressions"/>
  </div>
</div>

<script setup>
  import EnumCol from './components/EnumCol.vue'
  import WhiteLogo from './components/WhiteLogo.vue'
</script>

<style>
  @import './css/slide.css'
</style>

---
transition: fade-out
---

<div>
  <WhiteLogo uniqueClass='gradient-black-white'/>
  <div class="flex flex-row -mx-1">
    <EnumCol class="colColor1 " 
             icon ="📝" 
             title="Text-based" 
             paragraphText="Focus on the content with Markdown, and then style them later"/>
    <!-- <div class="w-0.5 bg-white"></div> -->
    <EnumCol class="colColor2 " 
             icon ="🎨" 
             title="Themable" 
             paragraphText="Themes can be shared and re-used as npm packages"/>
    <!-- <div class="w-0.5 bg-white"></div> -->
    <EnumCol class="colColor1 " 
             icon ="🧑‍💻" 
             title="Developer Friendly" 
             paragraphText="Code highlighting, live coding with autocompletion"/>
    <!-- <div class="w-0.5 bg-white"></div> -->
    <EnumCol class="colColor2  "
             icon ="🤹" 
             title="Interactive" 
             paragraphText="Embed Vue components to enhance your expressions" />
    <!-- <div class="w-0.5 bg-white"></div> -->
    <EnumCol class="colColor1 " 
             icon ="🎥" 
             title="Recording" 
             paragraphText="Built-in recording and camera view"/>
  </div>
</div>

<script setup>
  import EnumCol from './components/EnumCol.vue'
  import WhiteLogo from './components/WhiteLogo.vue'
</script>

<style>
  @import './css/slide.css'
</style>



---

<div class="colColor1 h-inherit">
  <WhiteLogo uniqueClass="customP"
             title="Code"
             paragraphText="Use code snippets and get the highlighting directly, and even types hover!"/>
  <div class="flex-container flex w-full mt-10 mr-10">
    <div class="text-white text-center flex-1">
      <h1>Code explanation</h1>
      <p> // TwoSlash enables TypeScript hover information<br>
          // and errors in markdown code blocks <br>
          // More at https://shiki.style/packages/twoslash</p>
    </div>
  <div class="code-container w-max  bg-transparent rounded mr-10 text-xs flex-1 code-block-shadow">

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

<div class="colColor1 h-inherit">
  <WhiteLogo uniqueClass="customP"
             title="Code"
             paragraphText="Use code snippets and get the highlighting directly, and even types hover!"/>
  <div class="flex-container flex w-full">
  <div class="code-container mt-10 ml-10 w-max bg-transparent rounded flex-1 code-block-shadow">

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

# Themes


---

## class: px-20

# Themes

Slidev comes with powerful theming support. Themes can provide styles, layouts, components, or even configurations for tools. Switching between themes by just **one edit** in your frontmatter:

<div grid="~ cols-2 gap-2" m="t-2">

```yaml
---
theme: default
---
```

```yaml
---
theme: seriph
---
```

<img border="rounded" src="https://github.com/slidevjs/themes/blob/main/screenshots/theme-default/01.png?raw=true" alt="">

<img border="rounded" src="https://github.com/slidevjs/themes/blob/main/screenshots/theme-seriph/01.png?raw=true" alt="">

</div>

Read more about [How to use a theme](https://sli.dev/guide/theme-addon#use-theme) and
check out the [Awesome Themes Gallery](https://sli.dev/resources/theme-gallery).

---

# Clicks Animations

You can add `v-click` to elements to add a click animation.

<div v-click>

This shows up when you click the slide:

```html
<div v-click>This shows up when you click the slide.</div>
```

</div>

<br>

<v-click>

The <span v-mark.red="3"><code>v-mark</code> directive</span>
also allows you to add
<span v-mark.circle.orange="4">inline marks</span>
, powered by [Rough Notation](https://roughnotation.com/):

```html
<span v-mark.underline.orange>inline markers</span>
```

</v-click>

<div mt-20 v-click>

[Learn more](https://sli.dev/guide/animations#click-animation)

</div>

---

# Motions

Motion animations are powered by [@vueuse/motion](https://motion.vueuse.org/), triggered by `v-motion` directive.

```html
<div
  v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }"
  :click-3="{ x: 80 }"
  :leave="{ x: 1000 }"
>
  Slidev
</div>
```

<div class="w-60 relative">
  <div class="relative w-40 h-40">
    <img
      v-motion
      :initial="{ x: 800, y: -100, scale: 1.5, rotate: -50 }"
      :enter="final"
      class="absolute inset-0"
      src="https://sli.dev/logo-square.png"
      alt=""
    />
    <img
      v-motion
      :initial="{ y: 500, x: -100, scale: 2 }"
      :enter="final"
      class="absolute inset-0"
      src="https://sli.dev/logo-circle.png"
      alt=""
    />
    <img
      v-motion
      :initial="{ x: 600, y: 400, scale: 2, rotate: 100 }"
      :enter="final"
      class="absolute inset-0"
      src="https://sli.dev/logo-triangle.png"
      alt=""
    />
  </div>

  <div
    class="text-5xl absolute top-14 left-40 text-[#2B90B6] -z-1"
    v-motion
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    Slidev
  </div>
</div>

<!-- vue script setup scripts can be directly used in markdown, and will only affects current page -->
<script setup lang="ts">
const final = {
  x: 0,
  y: 0,
  rotate: 0,
  scale: 1,
  transition: {
    type: 'spring',
    damping: 10,
    stiffness: 20,
    mass: 2
  }
}
</script>

<div
  v-motion
  :initial="{ x:35, y: 30, opacity: 0}"
  :enter="{ y: 0, opacity: 1, transition: { delay: 3500 } }">

[Learn more](https://sli.dev/guide/animations.html#motion)

</div>

---

# LaTeX

LaTeX is supported out-of-box. Powered by [KaTeX](https://katex.org/).

<div h-3 />

Inline $\sqrt{3x-1}+(1+x)^2$

Block

$$
{1|3|all}
\begin{aligned}
\nabla \cdot \vec{E} &= \frac{\rho}{\varepsilon_0} \\
\nabla \cdot \vec{B} &= 0 \\
\nabla \times \vec{E} &= -\frac{\partial\vec{B}}{\partial t} \\
\nabla \times \vec{B} &= \mu_0\vec{J} + \mu_0\varepsilon_0\frac{\partial\vec{E}}{\partial t}
\end{aligned}
$$

[Learn more](https://sli.dev/features/latex)

---

# Diagrams

You can create diagrams / graphs from textual descriptions, directly in your Markdown.

<div class="grid grid-cols-4 gap-5 pt-4 -mb-6">

```mermaid {scale: 0.5, alt: 'A simple sequence diagram'}
sequenceDiagram
    Alice->John: Hello John, how are you?
    Note over Alice,John: A typical interaction
```

```mermaid {theme: 'neutral', scale: 0.8}
graph TD
B[Text] --> C{Decision}
C -->|One| D[Result 1]
C -->|Two| E[Result 2]
```

```mermaid
mindmap
  root((mindmap))
    Origins
      Long history
      ::icon(fa fa-book)
      Popularisation
        British popular psychology author Tony Buzan
    Research
      On effectiveness<br/>and features
      On Automatic creation
        Uses
            Creative techniques
            Strategic planning
            Argument mapping
    Tools
      Pen and paper
      Mermaid
```

```plantuml {scale: 0.7}
@startuml

package "Some Group" {
  HTTP - [First Component]
  [Another Component]
}

node "Other Groups" {
  FTP - [Second Component]
  [First Component] --> FTP
}

cloud {
  [Example 1]
}

database "MySql" {
  folder "This is my folder" {
    [Folder 3]
  }
  frame "Foo" {
    [Frame 4]
  }
}

[Another Component] --> [Example 1]
[Example 1] --> [Folder 3]
[Folder 3] --> [Frame 4]

@enduml
```

</div>

Learn more: [Mermaid Diagrams](https://sli.dev/features/mermaid) and [PlantUML Diagrams](https://sli.dev/features/plantuml)

---

foo: bar
dragPos:
square: 691,32,167,\_,-16

---

dragPos:
square: -45,0,0,0

---
dragPos:
  square: -45,0,0,0
---

# Draggable Elements

Double-click on the draggable elements to edit their positions.

<br>

###### Directive Usage

```md
<img v-drag="'square'" src="https://sli.dev/logo.png">
```

<br>

###### Component Usage

```md
<v-drag text-3xl>
  <carbon:arrow-up />
  Use the `v-drag` component to have a draggable container!
</v-drag>
```

<v-drag pos="471,416,261,_,-15"undefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefinedundefined>
  <div text-center text-3xl border border-main rounded>
    Double-click me!
  </div>
</v-drag>

<img v-drag="'square'" src="https://sli.dev/logo.png">

###### Draggable Arrow

```md
<v-drag-arrow two-way />
```

<v-drag-arrow pos="67,452,253,46" two-way op70 />

---

src: ./pages/imported-slides.md
hide: false

---


---

# Monaco Editor

Slidev provides built-in Monaco Editor support.

Add `{monaco}` to the code block to turn it into an editor:

```ts {monaco}
import { ref } from "vue";
import { emptyArray } from "./external";

const arr = ref(emptyArray(10));
```

Use `{monaco-run}` to create an editor that can execute the code directly in the slide:

```ts {monaco-run}
import { version } from "vue";
import { emptyArray, sayHello } from "./external";

sayHello();
console.log(`vue ${version}`);
console.log(
  emptyArray<number>(10).reduce(
    (fib) => [...fib, fib.at(-1)! + fib.at(-2)!],
    [1, 1]
  )
);
```

---

layout: center
class: text-center

---

# Learn More

[Documentation](https://sli.dev) · [GitHub](https://github.com/slidevjs/slidev) · [Showcases](https://sli.dev/resources/showcases)

<PoweredBySlidev mt-10 />
