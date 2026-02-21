# # Week 06 – Smart User Dashboard (BOM & Storage Project)

**MEGA TEAM Frontend Track – Mid Level 2026**

### 🎯 Goal

Build an interactive dashboard that "remembers" the user and interacts with the browser's window and storage APIs.  
Use **only** JavaScript concepts from Lessons #098 to #114.

### 📁 Project Name

`smart-user-dashboard`

### 🛠️ What You Need to Build

**1. Top Bar & Navigation:**

- Display a **Digital Clock** (HH:MM:SS) that updates every second in real-time.
- A **"Log Out"** button that clears all stored data and reloads the page.

**2. Main Content Area:**

- **Welcome Section:** Ask for the user's name via `prompt()` on the first visit, then save it in `localStorage` to greet them every time they return.
- **Quick Notes:** A section where users can add short notes. When adding or deleting, you must use **DOM Traversing** and **Cloning**.
- **Theme Switcher:** Buttons to toggle between **Dark Mode** and **Light Mode**. The selected theme must persist (save in `localStorage`).

**3. Browser Controls (BOM):**

- A **"Back to Top"** button that stays hidden and only appears when the user scrolls down.
- A **"Reset Dashboard"** button that shows a `confirm()` box before wiping all notes and settings.

---

### 🚀 Required JavaScript Concepts – Use each at least once

| Lesson(s)    | Concept                            | Simple Place to Use It                                                    |
| ------------ | ---------------------------------- | ------------------------------------------------------------------------- |
| **#098–099** | **DOM Traversing & Cloning**       | Use `parentElement` to delete a note; `cloneNode` to add a new one.       |
| **#100–101** | **AddEventListener**               | Use professional event listeners for all buttons (No inline HTML events). |
| **#102–103** | **BOM (Alert, Confirm, Prompt)**   | `prompt` for name, `confirm` before resetting the dashboard.              |
| **#104–105** | **setTimeout / setInterval**       | `setInterval` for the clock; `setTimeout` for a welcome message.          |
| **#106–107** | **Window Location / Open & Close** | `location.reload()` when logging out or resetting.                        |
| **#108–109** | **Window Scroll / Focus**          | `window.scrollTo()` for the "Back to Top" button.                         |
| **#111–112** | **Local Storage**                  | **[Mandatory]** Save and retrieve the "Theme" and "User Name".            |
| **#113**     | **Session Storage**                | Save a "Session Start Time" that clears when the tab is closed.           |
| **#114**     | **BOM Challenge**                  | Combine storage and timers to create a "Time Spent" counter.              |

---

### ✅ Minimum Requirements Checklist

- [ ] Digital clock must update in real-time using `setInterval`.
- [ ] Use `localStorage` to keep the user's theme even after refreshing.
- [ ] Use `cloneNode(true)` to add new note elements to the list.
- [ ] Show the "Back to Top" button only after scrolling 500px (use `window.scrollY`).
- [ ] All data entry (Name, Notes) must be stored and retrieved from `localStorage`.
- [ ] Use `window.confirm()` before any "Delete All" or "Reset" action.

---

### 📂 Folder Structure

```text
smart-user-dashboard/
├── index.html
├── css/
│   └── style.css      (include styles for .dark-theme and .light-theme)
├── js/
│   └── main.js
└── README.md

### What to Submit
- Live demo link
- Screenshot (form + one example generated card)
- This table filled with where you used each concept

**Deadline:** Saturday – 11:59 PM Cairo Time

Small project – big learning.
Focus on clean code and comments.
You got this! 💪

Abdelrahman Ma3rouf Supervisor Frontend – MEGA TEAM
```
