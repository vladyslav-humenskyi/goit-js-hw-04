# goit-js-hw-03

GoIT Fullstack homework #3 for JavaScript: arrays, string ↔ array conversion and `for...of` loops.

**Live page:** [https://vladyslav-humenskyi.github.io/goit-js-hw-03/](https://vladyslav-humenskyi.github.io/goit-js-hw-03/) (open DevTools → Console to see the output)

## Tasks

| File | Function | What it does |
| --- | --- | --- |
| `js/task-1.js` | `slugify(title)` | Converts a title to a URL slug: lowercases it and joins the words with `-` (e.g. `"Arrays for beginners"` → `"arrays-for-beginners"`). |
| `js/task-2.js` | `makeArray(firstArray, secondArray, maxLength)` | Concatenates the two arrays and returns the result, truncated to the first `maxLength` elements if it is longer. |
| `js/task-3.js` | `filterArray(numbers, value)` | Returns a new array with only the numbers greater than `value`. |

Each file logs its sample calls to the console. `index.html` loads all three scripts as ES modules.

## Run locally

Serve the folder with any static server (for example the VS Code Live Server extension) and open `index.html`, then check the browser console.

## Structure

```
index.html
prettierrc.json
js/
  task-1.js
  task-2.js
  task-3.js
```
