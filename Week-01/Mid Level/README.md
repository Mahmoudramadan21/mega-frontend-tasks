# JavaScript Basics Mastery Challenge - MEGA TEAM

## Description
This challenge tests your **full understanding** of **"Learn JavaScript in Arabic 2021"** lessons **#001 to #018**.

You will build a **"Personal Card Generator"** using:
- VS Code + Live Server
- Chrome DevTools
- Clean JavaScript code
- All concepts from the 18 lessons

---

## Concepts Covered
- Setup & Tools (#001–#004)
- Code placement: inline, internal, external (#005)
- Comments & bad practices (#006)
- Output: `alert`, `console.log`, `document.write` (#007)
- Console methods + `%c` styling (#008)
- ECMAScript & `typeof` (#009–#010)
- Variables, naming rules, `var/let/const` (#011–#013)
- Strings + escape sequences (#014)
- Concatenation vs Template Literals (#015–#017)
- Arithmetic operators: `+ - * / % **` (#018)

---

## Project Structure
```
/JavaScript-Basics-Challenge
│
├─ index.html         # HTML structure (no JS yet)
├─ js/
│   └─ main.js        # Your JS code (TODOs)
├─ README.md          # This file (your answers)
└─ .gitignore         # (optional)
```

---

## Task Instructions

### 1. **Setup (#001–#004)**
- Create the folder and files
- Open in **VS Code**
- Install **Live Server**
- Open `index.html` → **"Open with Live Server"**
- Open **Chrome DevTools** (`F12`)

In `README.md`, add:
- 1–2 sentences: **"What is JavaScript?"** (in your own words)
- Screenshot of **Console tab**
- How you set up Live Server

---

### 2. **Complete `main.js` using TODOs**

```js
// Start of program - DO NOT DELETE
/*
  This project covers lessons #001 to #018
  of "Learn JavaScript in Arabic 2021"
*/

// TODO #1: Use console.log with %c styling
// TODO #2: Use console.table to show lesson info
// TODO #3: Use console.warn and console.error

// TODO #4: Declare variables with let and const (fullName, birthYear, city)
// TODO #5: Avoid var — explain why in a comment
// TODO #6: Show invalid variable names (commented)

// TODO #7: Use typeof to log data types

// TODO #8: Create a string with \n and \t

// TODO #9: Build a card using + (concatenation)
// TODO #10: Build the same card using template literals

// TODO #11: Calculate: salary, bonus, tax, net, monthly, 5% raise

// TODO #12: Write function generateCard() that:
//    - Gets #output
//    - Calculates age
//    - Generates random salary
//    - Builds card with template literals
//    - Updates DOM
//    - Logs to console with table

// TODO #13: Call generateCard() on page load

// TODO #14: Add onclick to button to regenerate card
```

---

### 3. **Update `index.html`**
- Add **inline script** (`alert`)
- Add **external script** (`main.js`)
- Add `onclick="generateCard()"` to button

---

### 4. **Testing & Debugging**
- Open DevTools
- Test in Console:
  ```js
  fullName = "Sara Ali"; generateCard();
  ```
- Set **breakpoint** in `generateCard()`
- Inspect **DOM** after button click

---

## Evaluation (100 Points)

| %   | Criteria |
|-----|--------|
| 15% | Setup + Live Server + DevTools screenshot |
| 15% | Clean comments + no bad practices |
| 15% | Console methods + `%c` styling |
| 15% | `let/const`, naming rules, avoid `var` |
| 20% | Template literals + concatenation + escape |
| 20% | Correct math + random data |
| +Bonus | Smooth button, nice UI, extra features |

---

## Author
- MEGA TEAM Frontend Mentor: **Mahmoud Ramadan**

---

## License
For **educational use only** within MEGA TEAM.
```

---

### 2. `index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Personal Card Generator</title>
  <style>
    body { font-family: Arial, sans-serif; text-align: center; margin-top: 50px; }
    .card { border: 2px solid #9333ea; padding: 20px; border-radius: 12px; max-width: 400px; margin: 20px auto; background: #f9f9f9; }
    button { padding: 10px 20px; font-size: 16px; background: #9333ea; color: white; border: none; border-radius: 8px; cursor: pointer; }
    button:hover { background: #7e1bc7; }
  </style>
</head>
<body>
  <h1>Personal Card Generator</h1>
  <div id="output" class="card"></div>
  <button>Generate New Card</button>

  <!-- TODO: Add inline script (alert) -->
  <!-- TODO: Add external script (main.js) -->
</body>
</html>
```

---

### 3. `js/main.js`

```js
// Start of program - DO NOT DELETE
/*
  This project covers lessons #001 to #018
  of "Learn JavaScript in Arabic 2021"
*/

// TODO #1: Use console.log with %c styling
// TODO #2: Use console.table to show lesson info
// TODO #3: Use console.warn and console.error

// TODO #4: Declare variables with let and const (fullName, birthYear, city)
// TODO #5: Avoid var — explain why in a comment
// TODO #6: Show invalid variable names (commented)

// TODO #7: Use typeof to log data types

// TODO #8: Create a string with \n and \t

// TODO #9: Build a card using + (concatenation)
// TODO #10: Build the same card using template literals

// TODO #11: Calculate: salary, bonus, tax, net, monthly, 5% raise

// TODO #12: Write function generateCard() that:
//    - Gets #output
//    - Calculates age
//    - Generates random salary
//    - Builds card with template literals
//    - Updates DOM
//    - Logs to console with table

// TODO #13: Call generateCard() on page load

// TODO #14: Add onclick to button to regenerate card
