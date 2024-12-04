---
layout: default
---

# Introduction

## Qu'est-ce qu'un framework ?

Un **framework** est une **structure préétablie** qui fournit un **ensemble d'outils**, de **bibliothèques** et de **conventions** pour faciliter le développement d'applications. C'est comme un "squelette" qui :

<div class="framework-features">

<div class="feature-box">
    <strong>Standardise</strong> le développement avec des patterns éprouvés
</div>

  <v-clicks>
    <div class="feature-box">
      <strong>Accélère</strong> la création d'applications en évitant de "réinventer la roue"
    </div>
  </v-clicks>

  <v-clicks>
    <div class="feature-box">
      <strong>Sécurise</strong> le code en appliquant les meilleures pratiques
    </div>
  </v-clicks>

  <v-clicks>
    <div class="feature-box">
      <strong>Organise</strong> la structure du projet de manière cohérente
    </div>
  </v-clicks>
</div>

<style>
.framework-features {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 2rem 3rem;
  max-width: 500px;
  margin: 2rem auto;
}

.feature-box {
  background: rgba(65, 105, 225, 0.1);
  border: 2px solid royalblue;
  border-radius: 8px;
  padding: 1rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  transition: all 0.3s ease;
  font-size: 0.8em;
  line-height: 1.3;
}

.feature-box strong {
  display: block;
  margin-bottom: 0.3rem;
  font-size: 1.1em;
  color: royalblue;
}

.feature-box:hover {
  transform: scale(1.05);
  background: rgba(65, 105, 225, 0.2);
}
</style>
