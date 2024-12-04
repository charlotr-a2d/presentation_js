---
layout: default
---

# Electron - Applications Desktop

<div>

- **Architecture Hybride :** Electron utilise **Chromium** pour le rendu de l'interface utilisateur et **Node.js** pour accéder aux API du système d'exploitation.

```typescript
// main.js
const { app, BrowserWindow, ipcMain } = require('electron');

function createWindow() {
  const win = new BrowserWindow({
    width: 800,
    height: 600,
    webPreferences: {
      nodeIntegration: true,
      contextIsolation: false,
    }
  });

  win.loadFile('index.html');
}

app.whenReady().then(createWindow);
```

</div>

<style>
  .slidev-layout {
    font-size: 0.9em;
  }
</style>