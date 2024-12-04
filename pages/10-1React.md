---
layout: default
---

# React - Le Champion du Front-End

<div>
<v-click>

- **Virtual DOM** : Permet des mises à jour efficaces de l'interface utilisateur.
```javascript
const element = <h1>Hello, world!</h1>;
ReactDOM.render(element, document.getElementById('root'));
```
</v-click>

<v-click>

- **Composants** : Réutilisables et modulaires, facilitant la maintenance.
```javascript
function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}
```
</v-click>

<v-click>

- **Store** : Centralisation de l'état pour une gestion simplifiée.
```javascript
const MyContext = React.createContext();
function App() {
  return (
    <MyContext.Provider value={{ user: 'John Doe' }}>
      <MyComponent />
    </MyContext.Provider>
  );
}
```
</v-click>
</div>

<style>
  .slidev-layout {
    font-size: 0.9em;
  }
</style>