# Week 04 – Advanced Todo Manager (Functions & Higher Order Functions Mastery)
**MEGA TEAM Frontend Track – 2026**

**Goal**  
Build a fully functional, clean, and modern **Todo List App** using **pure vanilla JavaScript** while proving mastery of **Lessons 57–78** from Elzero's JavaScript course.

### Project Name
`advanced-todo-manager`

### Required Features
- Add new todo (text + priority: low/medium/high)
- Mark as completed / uncompleted
- Edit todo text
- Delete todo
- Filter by: All / Active / Completed / Priority
- Search by text
- Show stats: Total, Completed, Pending (using reduce)

### Data Structure (Suggested)
```js
let todos = [
  { id: 1, text: "Learn Arrow Functions", completed: false, priority: "high" },
  // ...
];
```

### Required JavaScript Concepts (Must use every one)
| Lesson | Concept                        | Must Be Used In                                   |
|--------|--------------------------------|---------------------------------------------------|
| 57–58  | Function Declaration/Expression| addTodo(), deleteTodo(), toggleComplete()        |
| 59     | Return statements              | All functions must return something useful       |
| 60     | Default parameters             | addTodo(text, priority = "medium")               |
| 61     | Rest parameters                | logTodos(...items) or debug function             |
| 63–64  | Anonymous & Nested functions   | event listeners, setTimeout for success message  |
| 66     | Arrow Functions                | All callbacks, filters, event handlers           |
| 67–69  | Scope (global, function, block, lexical) | Properly scoped variables, no global pollution |
| 71–72  | map()                          | Render todos → map to HTML elements               |
| 73–74  | filter()                       | Filter by status or priority                      |
| 75–76  | reduce()                       | Calculate stats (total completed, etc.)           |
| 77     | forEach()                      | Alternative rendering or logging                  |
| 78     | Higher Order Functions Challenge | Chain: filter → map → forEach to render filtered list |

### Project Structure
```
advanced-todo-manager/
├── index.html
├── style.css          (clean, modern, responsive – optional flex/grid)
├── js/
│   └── main.js
├── README.md
└── screenshot.jpg
```

### README.md Must Include
1. Live demo link
2. Screenshot of app + console showing todos array
3. Table/list showing where each concept was used
4. Explanation of one clever use of reduce() or filter()+map() chain

### Bonus (Become a JS Wizard)
- Save todos to localStorage
- Sort by priority (high first)
- Keyboard shortcuts (Enter to add, Escape to clear input)
- Success animation/message using setTimeout + arrow function

### Rules
- No external libraries
- Clean, readable, heavily commented code
- Every function has a single responsibility
- Use arrow functions wherever possible
- Zero global variables when possible

When you finish this project correctly → You are officially **ready for DOM manipulation and real-world apps**.

Good luck, champion!  
**Mahmoud Ramadan**  
Frontend Mentor – MEGA TEAM
#MEGA_TEAM
