---
layout: default
---

# Performance et Impact Utilisateur

<div class="grid grid-cols-2 gap-8">

<div class="performance-issues space-y-6">

<v-click>

## Impact des Frameworks

### 🛠 Côté Développeur
- **Build Time**: Compilations npm de plusieurs minutes
- **Developer Experience**: Hot-reload ralenti sur grands projets
- **Ressources**: Forte consommation CPU/RAM en développement

</v-click>

<v-click>

### 👥 Côté Utilisateur Final
- **Poids**: Bundles > 1MB avec React + dépendances
- **Chargement**: Temps initial significatif
- **Mobile**: Performances dégradées sur appareils/réseaux limités

</v-click>

</div>

<div class="modern-solutions space-y-6">

<v-click>

## Solutions Modernes

### 🚀 Frameworks Nouvelle Génération
- **Svelte**: Compilation sans runtime
- **Solid.js**: Ultra-léger (7kb)
- **Qwik**: Chargement optimisé et intelligent

</v-click>

<v-click>

### ⚡️ Optimisation Avancée
- **Vite**: Builds instantanés (ESBuild)
- **Turbopack**: 10x plus rapide que Webpack
- **Code-Splitting**: Découpage automatique du code
- **Lazy Loading**: Import dynamique des composants

</v-click>

</div>

</div>