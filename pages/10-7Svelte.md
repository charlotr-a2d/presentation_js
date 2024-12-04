---
layout: default
---

# Svelte - Le Nouveau Challenger

<div>

- **Concept Clé : Compilation vs Runtime**  
  Svelte se distingue par sa **compilation** qui élimine le besoin d'un **runtime**

  Avantages : Code final plus léger, plus performant, propre

```javascript
<script>
  let count = 0;
  function increment() {
    count += 1;
  }
</script>

<main>
  <h1>Bienvenue sur Svelte!</h1>
  <button on:click={increment}>
    Cliquez-moi : {count}
  </button>
</main>
```
<v-click>

- **Le petit plus qui fait la différence : Stores intégrés**  
  Svelte propose des **stores** intégrés pour une gestion d'état réactive et simple.
</v-click>
</div>

<style>
  .slidev-layout {
    font-size: 0.9em;
  }
</style>