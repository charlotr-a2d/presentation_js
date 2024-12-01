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
  @apply bg-white text-black;
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


# Les Frameworks JavaScript
## Une Réflexion Stratégique

<div class="grid grid-cols-2 gap-8 mt-12">
  <div>
    <h3 class="text-xl mb-4">Objectifs</h3>
    <ul class="!list-none space-y-2">
      <li>🎯 Comprendre l'évolution des frameworks</li>
      <li>💡 Analyser les enjeux actuels</li>
      <li>🔄 Explorer les tendances futures</li>
      <li>⚖️ Développer un regard critique</li>
    </ul>
  </div>
  
  <div>
    <h3 class="text-xl mb-4">Questions clés</h3>
    <blockquote class="!mt-0">
      Pourquoi autant de frameworks ? <br>
      Sont-ils vraiment indispensables aujourd'hui ?
    </blockquote>
  </div>
</div>

<div class="absolute bottom-8">
  <span @click="$slidev.nav.next" class="px-4 py-2 rounded cursor-pointer bg-blue-600 text-white hover:bg-blue-700">
    Commencer <carbon:arrow-right class="inline"/>
  </span>
</div>

---
src: ./pages/001-explications-frameworks.md
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