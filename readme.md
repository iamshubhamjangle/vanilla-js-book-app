## About

Project is live at:

This project is made with Vanilla Javascript using the ES6 features (class, spread, rest)

## Snippets for reference

```js
// once DOM is loaded
document.addEventListener("DOMContentLoaded", UI.displayBooks);

// Element Selectors
document.getElementById("book-list");
document.querySelector("#book-list");

// Nodes
const row = document.createElement("tr");
row.innerHTML = "<td>Row Item</td>";
const list = document.appendChild(row);
row.parentElement.remove(); // to remove the node

// LocalStorage
localStorage.getItem("books") === null; // set local array to empty
localStorage.getItem("books"); // to read items

JSON.parse(); // READ operation
JSON.stringify(); // WRITE operation
```
