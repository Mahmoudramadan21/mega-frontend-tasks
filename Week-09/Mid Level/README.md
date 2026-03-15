# 🚀 Week 09 – Advanced OOP, Date/Time, Generators & Modules

**MEGA TEAM Frontend Track – Mid Level 2026**

### 🎯 Goal

Build a **Company Management Dashboard (Console-Based or UI)** that relies on Object-Oriented Programming (OOP) principles. You will manage employee records, track hiring dates, generate unique serial numbers automatically, and organize your code into clean, scalable modules.
Use **only** JavaScript concepts from Lessons #147 to #168.

### 📁 Project Name

`mega-oop-dashboard`

### 🛠️ What You Need to Build

**1. Employee Management System (OOP & Encapsulation):**

- Create a base `Employee` class and an `Admin` subclass.
- Protect sensitive data (like salaries) using Class Encapsulation (Private Properties).
- Use Static properties to count the total number of created employees.

**2. Automated ID Generator (Generators):**

- Build a Generator Function that yields a unique, incremental ID (e.g., `#EMP-1`, `#EMP-2`) every time a new employee is added to the system, ensuring infinite unique IDs.

**3. Action Tracker (Date & Time):**

- Every time an employee is created, record the exact creation Date and Time.
- Add a feature to calculate how many days an employee has been in the company.

**4. Code Organization (Modules):**

- Avoid writing everything in one massive file. Split your classes, generators, and helper functions into separate JavaScript files and connect them using Import/Export.

---

### 🚀 Required JavaScript Concepts – Use each at least once

| Lesson(s)    | Concept                                  | Simple Place to Use It                                                                                                                         |
| :----------- | :--------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------- |
| **#147–151** | **Constructor Functions & Properties**   | Understand the core of object creation before moving to classes.                                                                               |
| **#152–154** | **Classes, Inheritance & Encapsulation** | **[Mandatory]** Create a base `User` class. Extend it to create an `Admin` class. Make the `salary` property private (`#salary`).              |
| **#155–156** | **Prototypes**                           | Add a custom method to the `String` or `Array` prototype (e.g., a method that formats names automatically) using Prototype Chain.              |
| **#157–158** | **Object Meta Data & Descriptors**       | Use `Object.defineProperty` to create a `companyName` property that is `writable: false` and `configurable: false` so it can never be changed. |
| **#159–163** | **Date & Time Methods**                  | Use `new Date()` to set a `hiringDate` for each user. Create a method to format it into `YYYY-MM-DD`.                                          |
| **#164–166** | **Generator Functions**                  | **[Mandatory]** Write a `function* idGenerator()` that yields infinite, sequential IDs for new employees.                                      |
| **#167–168** | **Modules (Import / Export)**            | **[Mandatory]** Export your classes from `models.js` and import them into `main.js` using both Named and Default exports.                      |

---

### ✅ Minimum Requirements Checklist

- [ ] **Class Structure:** Create at least one Parent Class and one Child Class using the `extends` keyword.
- [ ] **Data Privacy:** Hide at least one property using the `#` symbol (Encapsulation) and create a getter method to read it safely.
- [ ] **Immutable Properties:** Use Object Descriptors to lock down a specific property so it cannot be deleted or modified.
- [ ] **Date Formatting:** Include a method that prints a user-friendly timestamp (e.g., "Hired on: 15 October 2026") using Date methods.
- [ ] **Infinite Generator:** Implement a generator function that assigns a new ID sequentially without using standard loops.
- [ ] **Modular Architecture:** The project must have at least 3 separate `.js` files connected via `import` and `export`.

---

### 📂 Folder Structure

```text
mega-oop-dashboard/
├── index.html
├── css/
│   └── style.css
├── js/
│   ├── modules/
│   │   ├── User.js        (Contains User and Admin classes)
│   │   └── generators.js  (Contains the ID Generator function)
│   └── main.js            (Imports modules and executes the logic)
└── README.md
```
