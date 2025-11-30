# Week 3 – Dynamic Products Store  
JavaScript Arrays & Loops Mastery Challenge

**MEGA TEAM Frontend Track – Mid-Level 2025**

You’ve just finished lessons **#040 to #056** of Elzero’s legendary JavaScript course.  
Now it’s time to prove you truly own **Arrays** and **Loops** by building something real, clean, and fully dynamic — no tutorials, no copying, just pure understanding.

### Challenge Goal
Build a **Dynamic Products Store** that:
- Displays product cards from a JavaScript array
- Lets you add a new product
- Lets you delete a product
- Supports search by title
- Can sort products by price (ascending/descending)
- Updates instantly in the browser (no page refresh)

This single project will force you to use **every single concept** from lessons 40–56.

### Project Structure
```
dynamic-products-store/
├── index.html
├── style.css           ← Clean and simple styling only
├── js/
│   └── main.js         ← All your JavaScript lives here
├── assets/
│   └── images/         ← Put 6–8 product images
├── README.md
└── screenshot.jpg      ← Final result (required)
```

### Initial Products Array (put this at the top of main.js)
```js
let products = [
  { id: 1, title: "Laptop Pro",       price: 25000, category: "Electronics", inStock: true },
  { id: 2, title: "Wireless Headphones", price: 1200,  category: "Accessories", inStock: true },
  { id: 3, title: "Smart Watch",      price: 8500,  category: "Electronics", inStock: false },
  { id: 4, title: "USB Cable",        price: 150,   category: "Accessories", inStock: true },
  { id: 5, title: "Mechanical Keyboard", price: 3200, category: "Electronics", inStock: true },
  { id: 6, title: "Mouse Pad",        price: 350,   category: "Accessories", inStock: true }
];
```

### Required Concepts – You MUST use each one

| Lesson | Concept                     | Where to use it                              |
|-------|-----------------------------|----------------------------------------------|
| #040–041 | `length`                  | Check if store is empty, count items         |
| #042   | `push()`, `unshift()`, `pop()`, `shift()` | Add & remove products                  |
| #043   | `indexOf()`, `includes()`   | Search functionality                         |
| #044   | `sort()`                    | Sort by price (toggle asc/desc)              |
| #045   | `slice()`                   | Optional: show only first N products         |
| #046   | `join()`, `concat()`        | Build category list or combine arrays        |
| #048–050 | `for`, `for...of`, nested loops | Rendering products + filtering             |
| #051   | `break`, `continue`, `label`| Skip out-of-stock items or early exit        |
| #053   | Add products to page dynamically | Core of the project                         |
| #054–055 | `while` & `do...while`    | Re-index IDs after deletion, or retry logic  |
| #056   | Loop Challenge              | Solved and commented in code                 |

### Minimal HTML (example)
```html
<h1>MEGA Store</h1>

<div class="controls">
  <input type="text" id="search" placeholder="Search products..." />
  <button onclick="addRandomProduct()">Add Random Product</button>
  <button onclick="sortByPrice()">Sort by Price</button>
</div>

<div id="products-container" class="products"></div>
```

### Core Functions You Must Write in main.js
1. `renderProducts()` → loops and injects HTML
2. `addRandomProduct()` → pushes new object + re-render
3. `deleteProduct(id)` → remove by id + re-render
4. `searchProducts()` → filter using `includes()`
5. `sortByPrice()` → toggle between ascending/descending

### README.md Must Include
1. Live demo link (GitHub Pages recommended)
2. Final screenshot
3. Table showing exactly where you used each lesson #040–#056  
   (copy the template below)

```markdown
| Lesson | Concept Used        | Line / Function       |
|--------|---------------------|-----------------------|
| #042   | push()              | addRandomProduct()    |
| #044   | sort()              | sortByPrice()         |
| #051   | continue            | renderProducts() loop |
| ...    | ...                 | ...                   |
```

### Rules
- No external libraries
- No frameworks (React, etc.)
- Clean, commented, readable code
- Every lesson from #040 to #056 must appear and be commented

### Bonus (Legend Status)
- Keyboard support for search
- “Out of stock” products appear semi-transparent
- Smooth animations on add/delete (CSS only)
- Re-index IDs after deletion using a `while` loop

### Submission Checklist
- [ ] Live demo works perfectly
- [ ] All required concepts used and listed in README
- [ ] Screenshot included
- [ ] Code is clean with clear comments
- [ ] Public GitHub repo

### Deadline
**Friday – 12:00 AM (midnight) Cairo time**

The first 5 perfect submissions get:
- Personal video review from me
- Official “Arrays & Loops Master” certificate
- Permanent spot in MEGA TEAM Hall of Fame

When you finish this project correctly, you are no longer a beginner.  
You are officially **Mid-Level JavaScript ready** and can jump into DOM manipulation and React without fear.

Let’s see who becomes the first Arrays & Loops Master of 2025.

Good luck!

**Mahmoud Ramadan**  
Frontend Mentor – MEGA TEAM

#MEGA_TEAM #JavaScriptMastery