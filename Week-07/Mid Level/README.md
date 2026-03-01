# 🚀 Week 07 – Advanced Data Structures & ES6 Magic

**MEGA TEAM Frontend Track – Mid Level 2026**

### 🎯 Goal

Build a **Smart Inventory & Employee Tracker** that heavily relies on modern JavaScript features. You will manipulate complex data, ensure uniqueness, map relational data, and write ultra-clean code using ES6+ syntax.  
Use **only** JavaScript concepts from Lessons #115 to #133.

### 📁 Project Name

`smart-data-manager`

### 🛠️ What You Need to Build

**1. Data Extractor (The Destructuring Area):**

- You will be provided with a complex, nested mock Object/Array containing Employee data (Name, Age, Address, nested Skills, etc.).
- You must display specific employee details on the page by extracting them using **Destructuring** (No traditional `object.property` chaining allowed here).

**2. Unique Tags & Skills Manager:**

- An input field where the user can add "Skills" or "Tags" to the system.
- You must use a **Set** to store these tags so that duplicate entries are automatically ignored.

**3. Permissions & Metadata Dictionary:**

- Use a **Map** to link specific DOM elements (like Employee Cards) directly to an object holding their hidden metadata (e.g., Salary, Access Level) without polluting the DOM with `data-` attributes.

**4. Array Analytics Panel:**

- A section that analyzes your data using modern array methods to show real-time stats (e.g., "Are _all_ employees active?", "Is _any_ employee an Admin?").

---

### 🚀 Required JavaScript Concepts – Use each at least once

| Lesson(s)    | Concept                                    | Simple Place to Use It                                                                                     |
| :----------- | :----------------------------------------- | :--------------------------------------------------------------------------------------------------------- |
| **#115–122** | **Destructuring (Arrays, Objects, Mixed)** | Extract nested employee info. Use swapping `[a, b] = [b, a]` to reorder two high-priority tasks.           |
| **#123–124** | **Set & WeakSet**                          | Store unique "Skills". Convert an array with duplicates into a clean array using `Set`.                    |
| **#125–127** | **Map & WeakMap**                          | **[Mandatory]** Map a physical DOM Node (like a button or card) to an object containing its configuration. |
| **#128**     | **Array.from()**                           | Convert a `NodeList` of generated items or a `String` into a pure Array to manipulate it.                  |
| **#130–131** | **Array.some() & Array.every()**           | Check if `every()` employee has a specific skill, or if `some()` employee is on vacation.                  |
| **#132**     | **Spread Syntax (`...`)**                  | Combine two arrays of data together, or use it to clone objects securely.                                  |

---

### ✅ Minimum Requirements Checklist

- [ ] Extract at least 5 deep properties from a complex object using **Object/Array Destructuring**.
- [ ] Implement a feature to swap the values of two variables using Destructuring.
- [ ] Create a "Unique Skills" list where adding a duplicate string is blocked natively by using a `new Set()`.
- [ ] Link a DOM element to an object using a `new Map()`. (Example: Clicking a user card fetches data from the Map using the card element as the key).
- [ ] Use `Array.every()` to display a boolean status (e.g., "System Secure: true").
- [ ] Use `Array.some()` to trigger a warning (e.g., "Warning: Admin present").
- [ ] Merge two arrays visually on the screen using the **Spread Operator**.

---

### 📂 Folder Structure

```text
smart-data-manager/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js      (All your ES6 magic goes here)
└── README.md
```
