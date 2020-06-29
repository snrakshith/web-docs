# Babel Plugin:

## It has 3 stage's

- Parse
- It has 2 phases
  - Traverse
  - Transform
- Generatation of Code

---

## Packages used :

- `babylon.js` ==> Parse
- `@babel/traverse` ==> Transform & Traverse
- `@babel/generate` ==> Generation

## !! Remember to follow convention

> babel-plugin-`package-name`

- astexplorer.net

### `Build Task :`

```html
"npm run build": "babel src/ -d lib -plugins ../plugins/plugin.js"
```

---

## Folder Structure

```html
src / plugins / lib /
```
