# 🚀 Week 08 – Advanced Selectors & Responsive Mastery

### **MEGA TEAM Frontend Track – Beginners Level 2026**

---

## 🎯 Goal

Build a **Fully Responsive Landing Page** without relying on external libraries like Bootstrap. You will create your own **mini CSS framework**, use **Advanced Selectors** to style elements cleanly without cluttering your HTML with classes, and make the layout look perfect on all screen sizes using **Media Queries**.

---

## 📂 Project Details

- **Project Name:** `responsive-framework-ui`
- **Supervisor:** Abdelrahman Ma3rouf Supervisor frontend

---

## 🛠️ Required CSS Concepts (The Mastery Challenge)

You must implement each of these concepts at least once in your project:

| Lesson        | Concept                             | Implementation Idea                                                                                                           |
| :------------ | ----------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| **#78 - #82** | `Advanced CSS Selectors`            | Use `:nth-child()`, `:not()`, and attribute selectors (e.g., `[type="text"]`) to style lists and form inputs cleanly.         |
| **#83 - #85** | `Media Queries & Responsive Design` | **[Mandatory]** Use `@media` rules to change a 3-column grid on desktop to a 1-column layout on mobile devices.               |
| **#86**       | `Create Your Framework`             | Build reusable utility classes (e.g., `.text-center`, `.flex-between`, `.mb-20`, `.container`) and use them in HTML.          |
| **#87**       | `CSS Global Values`                 | Use `inherit`, `initial`, or `unset` to control styling behavior, like resetting button backgrounds or inheriting typography. |
| **#88**       | `The End & Best Practices`          | Keep your code clean, well-commented, and structurally organized separating your framework from main styles.                  |

---

## 📝 Project Requirements Checklist

- [ ] **Custom Mini-Framework:** Create a separate CSS file or section with reusable utility classes (padding, margin, flexbox alignments, text-alignments) and use them across your HTML.
- [ ] **Advanced Selectors Usage:** Style a specific section (like a pricing table or a list of features) using advanced selectors like `:nth-child(even/odd)`, `::before`, `::after`, and direct child selectors `>` instead of adding individual classes to every element.
- [ ] **Fully Responsive Layout:** Your webpage must break down gracefully. Elements side-by-side on desktop should stack perfectly on mobile phones (`max-width: 767px`) and tablets (`max-width: 991px`).
- [ ] **Container System:** Implement a `.container` class with dynamic widths based on the screen size using Media Queries (Standard approach).
- [ ] **Global Values:** Explicitly use `inherit` or `unset` on at least two elements (e.g., making link colors inherit their parent's color).

---

## 📂 Folder Structure

```text
responsive-framework-ui/
├── index.html
├── css/
│   ├── framework.css    # Your reusable utility classes
│   ├── style.css        # Specific styles for the landing page
├── assets/
│   └── images/
└── README.md
```
