---
layout: default
---

# React Native - Mobile Cross-Platform

<div>

- **Concept Clé : Bridge Natif**  
  React Native utilise un **bridge** pour la communication entre le code **JavaScript** et les composants **natifs**, permettant une expérience utilisateur fluide et performante.

```javascript
// Exemple de composant React Native
import React from 'react';
import { Text, View, Button } from 'react-native';

export default function App() {
  return (
    <View style={{ flex: 1, justifyContent: 'center', alignItems: 'center' }}>
      <Text>Bienvenue sur React Native!</Text>
      <Button title="Cliquez-moi" onPress={() => alert('Bouton cliqué!')} />
    </View>
  );
}
```
<v-click>

- **Le petit plus qui fait la différence : Expo**  
  Expo permet de déployer en utilisant le build sur le cloud
</v-click>
</div>

<style>
  .slidev-layout {
    font-size: 0.9em;
  }
</style>