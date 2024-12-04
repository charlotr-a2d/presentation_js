---
layout: default
---

# Flutter - Le Framework Mobile Polyvalent

<div>

- **Concept Clé : UI Déclarative et Widgets**  
  Flutter utilise une approche **déclarative** pour l'UI, où vous définissez l'état souhaité, et Flutter gère les mises à jour. 
  
  Les **Widgets** sont les blocs de construction de l'UI, facilitant une création intuitive et concise.

```dart
  return MaterialApp(
    home: Scaffold(
      appBar: AppBar(
        title: Text('Bienvenue sur Flutter!'),
      ),
      body: Center(
        child: ElevatedButton(
          onPressed: () {
            showDialog(
              context: context,
              builder: (context) => AlertDialog(
                content: Text('Bouton cliqué!'),
              ),
            );
          },
          child: Text('Cliquez-moi'),
...
```
</div>

<style>
  .slidev-layout {
    font-size: 0.9em;
  }
</style>

