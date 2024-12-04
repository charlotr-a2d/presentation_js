---
layout: default
---

# React - Le Champion du Front-End

<div>
<v-click>

- **Router** : Système de routage puissant pour la navigation et le chargement paresseux.
```typescript
import { NgModule } from '@angular/core';
import { RouterModule, Routes } from '@angular/router';
import { HomeComponent } from './home/home.component';

const routes: Routes = [
  { path: '', component: HomeComponent }
];

@NgModule({
  imports: [RouterModule.forRoot(routes)],
  exports: [RouterModule]
})
export class AppRoutingModule {}
```
</v-click>
</div>

<style>
  .slidev-layout {
    font-size: 0.9em;
  }
</style>