---
layout: default
---

# Diversité des Frameworks

<div class="flex flex-wrap justify-center gap-4">

<div class="framework-bubble">
  <img src="/logos/react.svg" alt="React Logo" class="w-12 h-12 mb-2" />
  <h3 class="text-lg font-bold">React</h3>
  <div class="bubble-content">
    <p class="text-sm">UI flexible et modulaire</p>
    <p class="text-sm">Écosystème riche</p>
    <img src="/logos/meta.svg" alt="Meta Logo" class="company-logo" />
    <p class="text-xs">Maintenu par Meta</p>
  </div>
</div>

<div class="framework-bubble">
  <img src="/logos/vue.svg" alt="Vue Logo" class="w-12 h-12 mb-2" />
  <h3 class="text-lg font-bold">Vue</h3>
  <div class="bubble-content">
    <p class="text-sm">Framework progressif</p>
    <img src="/logos/opensource.svg" alt="Open Source Logo" class="company-logo" />
    <p class="text-xs">Communauté Open Source</p>
  </div>
</div>

<div class="framework-bubble">
  <img src="/logos/angular.svg" alt="Angular Logo" class="w-12 h-12 mb-2" />
  <h3 class="text-lg font-bold">Angular</h3>
  <div class="bubble-content">
    <p class="text-sm">Solutions Enterprise</p>
    <p class="text-sm">Framework complet</p>
    <img src="/logos/google.svg" alt="Google Logo" class="company-logo" />
    <p class="text-xs">Soutenu par Google</p>
  </div>
</div>

<div class="framework-bubble trends">
  <h3 class="text-lg font-bold">Tendances 🚀</h3>
  <div class="bubble-content">
    <div class="trend-item">
      <img src="/logos/nextjs.svg" alt="Next.js Logo" class="w-6 h-6" />
      <p class="text-sm">SSR avec Next.js/Nuxt</p>
    </div>
    <div class="trend-item">
      <img src="/logos/svelte.svg" alt="Svelte Logo" class="w-6 h-6" />
      <p class="text-sm">Compilation (Svelte)</p>
    </div>
    <div class="trend-item">
      <img src="/logos/vite.svg" alt="Vite Logo" class="w-6 h-6" />
      <p class="text-sm">Performance (Vite)</p>
    </div>
  </div>
</div>

</div>

<style>
.framework-bubble {
  @apply bg-white rounded-xl p-4 shadow-md text-center w-48 transition-transform hover:scale-105;
}

.bubble-content {
  @apply mt-2 space-y-2;
}

.company-logo {
  @apply w-6 h-6 mx-auto my-1;
}

.trend-item {
  @apply flex items-center gap-2 p-1;
}

.trends {
  @apply bg-gradient-to-br from-blue-50 to-purple-50;
}
</style>