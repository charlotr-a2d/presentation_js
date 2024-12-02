---
theme: default
background: white
class: 'text-black'
highlighter: shiki
lineNumbers: false
drawings:
  persist: false
css: unocss
defaults:
  layout: default
  background: white
  class: 'text-black'
---

<style>
/* Styles globaux */
.slidev-layout {
  @apply bg-white text-black relative;
  
  /* Style de base pour tous les textes */
  font-family: system-ui, -apple-system, sans-serif;
  line-height: 1.6;
}


.slidev-layout .content-container {
  @apply mx-auto max-w-4xl px-8 py-12;
}

.slidev-layout h1 {
  @apply text-4xl font-bold mb-12;
}

.slidev-layout h2 {
  @apply text-3xl font-semibold mb-8;
}

.slidev-layout h3 {
  @apply text-2xl font-semibold mb-6;
}

.slidev-layout ul {
  @apply space-y-4;
}


.slidev-layout blockquote {
  @apply text-gray-700 italic border-l-4 border-blue-600 pl-4 bg-gray-100 p-4 rounded-r;
}

</style>

<div class="flex flex-col items-center justify-center p-30">
  <div class="text-center space-y-8">
    <h1 class="text-6xl font-bold bg-gradient-to-r from-blue-600 to-purple-600 bg-clip-text text-transparent px-8">
      Les Frameworks JavaScript
    </h1>    
    <div class="mt-16 space-y-6">
      <h3 class="text-2xl font-medium text-gray-700">
        Réflexion autour de l'écosystème des frameworks JavaScript
      </h3>      
      <div class="mt-24 text-gray-600 space-y-3">
        <p class="text-xl">Présenté par</p>
        <p class="text-2xl font-semibold">Charlot Rodolphe</p>
        <p class="text-lg font-medium">A2Display</p>
      </div>
    </div>
  </div>
</div>

<style>
.slidev-layout {
  @apply bg-gradient-to-br from-gray-50 to-gray-100;
}
</style>

---
src: ./pages/01-explications-frameworks.md
---

---
src: ./pages/01-pourquoi.md
---

---
src: ./pages/02-contexte.md
---

---
src: ./pages/03-exigences.md
---

---
src: ./pages/04-diversite.md
---

---
src: ./pages/05-recul.md
---

---
src: ./pages/06-productivite.md
---

---
src: ./pages/07-fragmentation.md
---

---
src: ./pages/08-performance.md
---

---
src: ./pages/09-hype.md
---

---
src: ./pages/10-frontend.md
---

---
src: ./pages/11-fullstack.md
---

---
src: ./pages/12-multiplateforme.md
---

---
src: ./pages/13-minimalisme.md
---

---
src: ./pages/14-unification.md
---

---
src: ./pages/15-ethique.md
---

---
src: ./pages/16-synthese.md
---

---
src: ./pages/17-questions.md
---

---
src: ./pages/18-conclusion.md
---