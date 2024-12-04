---
layout: default
---

# Angular - La Solution Entreprise

<div>

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
</div>

<style>
  .slidev-layout {
    font-size: 0.9em;
  }
</style>