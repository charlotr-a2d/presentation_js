---
layout: default
---

# L'Évolution des Frameworks JavaScript

<div class="grid-container">

<v-click>
<div class="era">
  <h3>2006-2010</h3>
  <div class="framework">
    <h4>jQuery</h4>
    <p>Simplification DOM & AJAX</p>
  </div>
  <div class="framework">
    <h4>Backbone.js</h4>
    <p>MVC côté client</p>
  </div>
</div>
</v-click>

<v-click>
<div class="era">
  <h3>2013-2015</h3>
  <div class="framework">
    <h4>React</h4>
    <p>Virtual DOM & Composants</p>
  </div>
  <div class="framework">
    <h4>Vue.js</h4>
    <p>Progressive Framework</p>
  </div>
</div>
</v-click>

<v-click>
<div class="era">
  <h3>2016-2019</h3>
  <div class="framework">
    <h4>Angular</h4>
    <p>Enterprise TypeScript</p>
  </div>
  <div class="framework">
    <h4>Svelte</h4>
    <p>Compilation sans runtime</p>
  </div>
  <div class="framework">
    <h4>Next.js</h4>
    <p>Fullstack React</p>
  </div>
</div>
</v-click>

<v-click>
<div class="era">
  <h3>2020+</h3>
  <div class="framework">
    <h4>Vite.js</h4>
    <p>Build ultra-rapide</p>
  </div>
  <div class="framework">
    <h4>SvelteKit</h4>
    <p>Simple & performant</p>
  </div>
</div>
</v-click>

</div>

<style>
.grid-container {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 2rem;
  margin: 2rem 0;
}

.era {
  text-align: center;
  padding: 1rem;
  background: #f5f5f5;
  border-radius: 8px;
}

.framework {
  margin: 1rem 0;
  padding: 0.8rem;
  background: white;
  border-radius: 6px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

h3 {
  color: #2c3e50;
  margin-bottom: 1rem;
}

h4 {
  color: #42b883;
  margin: 0;
}

p {
  margin: 0.5rem 0 0;
  font-size: 0.9rem;
  color: #666;
}
</style>

<!--
Notes:
Évolution : DOM → Components → Compilation → Zero-Runtime
Chaque ère apporte son innovation majeure
-->